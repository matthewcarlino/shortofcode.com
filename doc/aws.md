# AWS things

## Parts and Pieces

Route 53 handles resolution with ACM contributing CNAMEs for the certificate.
`A` records resolve to the Cloudfront arrangement which pull from the S3
bucket.  So 4 services in all.

- Route 53
- ACM
- CloudFront
- S3


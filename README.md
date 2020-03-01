# thwoo.party

## deploy

```
aws s3 sync ./root/ s3://thwoo.party
aws cloudfront create-invalidation --distribution-id E39EM8LLCCGSAO --paths "/*"
```

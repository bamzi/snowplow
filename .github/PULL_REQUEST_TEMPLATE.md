/!\ IMPORTANT /!\

As explained in the blog post here https://snowplowanalytics.com/blog/2020/07/16/changing-releasing/ all the components of Snowplow pipeline have been moved to their own repo, PRs should be created directly on the appropriate repo :

Trackers
- Android: https://github.com/snowplow/snowplow-android-tracker
- .NET: https://github.com/snowplow/snowplow-dotnet-tracker
- Go: https://github.com/snowplow/snowplow-golang-tracker
- JAVA: https://github.com/snowplow/snowplow-java-tracker
- Javascript: https://github.com/snowplow/snowplow-javascript-tracker
- Node.js: https://github.com/snowplow/snowplow-nodejs-tracker
- Objective-C: https://github.com/snowplow/snowplow-objc-tracker
- PHP: https://github.com/snowplow/snowplow-php-tracker
- Python: https://github.com/snowplow/snowplow-python-tracker
- React Native: https://github.com/snowplow-incubator/snowplow-react-native-tracker
- Ruby: https://github.com/snowplow/snowplow-ruby-tracker
- Scala: https://github.com/snowplow/snowplow-scala-tracker
- Unity: https://github.com/snowplow/snowplow-unity-tracker

Collector: https://github.com/snowplow/stream-collector

Enrich: https://github.com/snowplow/enrich

Loaders
- BigQuery (streaming): https://github.com/snowplow-incubator/snowplow-bigquery-loader
- Redshift / Postgres (batch): https://github.com/snowplow/snowplow-rdb-loader
- Snowflake (batch): https://github.com/snowplow-incubator/snowplow-snowflake-loader
- Google Cloud Storage (streaming): https://github.com/snowplow-incubator/snowplow-google-cloud-storage-loader
- Amazon S3 (streaming): https://github.com/snowplow/snowplow-s3-loader
- Postgres (streaming): https://github.com/snowplow-incubator/snowplow-postgres-loader
- Elasticsearch (streaming): https://github.com/snowplow/snowplow-elasticsearch-loader

Testing
- Mini: https://github.com/snowplow/snowplow-mini
- Micro: https://github.com/snowplow-incubator/snowplow-micro

Parsing enriched event

- Analytics SDK Scala: https://github.com/snowplow/snowplow-scala-analytics-sdk
- Analytics SDK Python: https://github.com/snowplow/snowplow-python-analytics-sdk
- Analytics SDK .NET: https://github.com/snowplow/snowplow-dotnet-analytics-sdk
- Analytics SDK Javascript: https://github.com/snowplow-incubator/snowplow-js-analytics-sdk/

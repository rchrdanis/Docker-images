Markdown
# 🐳 Useful Docker Images for Local Development

A curated collection of essential Docker images for backend development, testing, and observability.

## 🛠️ Dev Tools & Databases

| Service | Image | Description | Links |
| :--- | :--- | :--- | :--- |

| **PostgreSQL** | `postgres:alpine` | The world's most advanced open source relational database. The `alpine` tag is lightweight. | [Docs](https://www.postgresql.org/docs/) • [Docker Hub](https://hub.docker.com/_/postgres) |
| **Redis** | `redis:alpine` | In-memory data structure store, used as a database, cache, and message broker. | [Docs](https://redis.io/documentation) • [Docker Hub](https://hub.docker.com/_/redis) |

## ☁️ AWS Platform (Local Emulators)

| Service | Image | Description | Links |
| :--- | :--- | :--- | :--- |
| **LocalStack** | `localstack/localstack` | A fully functional local cloud stack. Mocks AWS services (S3, SQS, Lambda, DynamoDB) locally. | [Docs](https://docs.localstack.cloud/) • [Docker Hub](https://hub.docker.com/r/localstack/localstack) |

## ☁️ Google Cloud Platform (Local Emulators)

| Service | Image | Description | Links |
| :--- | :--- | :--- | :--- |
| **GCP Emulators** | `google/cloud-sdk:emulators` | Official SDK containing emulators for Pub/Sub, Firestore, Datastore, Spanner, and Bigtable. | [Docs](https://cloud.google.com/sdk/gcloud/reference/beta/emulators) • [Docker Hub](https://hub.docker.com/r/google/cloud-sdk) |
| **Fake GCS** | `fsouza/fake-gcs-server` | Lightweight emulator for Google Cloud Storage (GCS). Essential if you use Spring Cloud GCP Storage. | [GitHub](https://github.com/fsouza/fake-gcs-server) • [Docker Hub](https://hub.docker.com/r/fsouza/fake-gcs-server) |

## 📨 Messaging & Streaming

| Service | Image | Description | Links |
| :--- | :--- | :--- | :--- |
| **Apache Kafka** | `apache/kafka:latest` | Open-source distributed event streaming platform. (Native KRaft mode recommended for local dev). | [Docs](https://kafka.apache.org/documentation/) • [Docker Hub](https://hub.docker.com/r/apache/kafka) |
| **Kafka UI** | `provectuslabs/kafka-ui` | A versatile, user-friendly web interface for managing Apache Kafka clusters. | [GitHub](https://github.com/provectus/kafka-ui) • [Docker Hub](https://hub.docker.com/r/provectuslabs/kafka-ui) |

## 🛡️ Security & Secrets Management

| Service | Image | Description | Links |
| :--- | :--- | :--- | :--- |
| **HashiCorp Vault** | `hashicorp/vault` | Tool for securely accessing secrets (API keys, passwords, certificates). Standard in enterprise Spring Cloud configs. | [Docs](https://developer.hashicorp.com/vault/docs) • [Docker Hub](https://hub.docker.com/r/hashicorp/vault) |

## 🔍 Observability & Tracing

| Service | Image | Description | Links |
| :--- | :--- | :--- | :--- |
| **Zipkin** | `openzipkin/zipkin` | Distributed tracing system. Helps gather timing data to troubleshoot latency in microservices. | [Docs](https://zipkin.io/) • [Docker Hub](https://hub.docker.com/r/openzipkin/zipkin) |

# 📧 Email & Notifications

| Service | Image | Description | Links |
| :--- | :--- | :--- | :--- |
| **Mailpit** | `axllent/mailpit` | An SMTP testing tool for developers. Captures emails sent by your app so they don't go to real users. (Modern replacement for MailHog). | [GitHub](https://github.com/axllent/mailpit) • [Docker Hub](https://hub.docker.com/r/axllent/mailpit) |

---

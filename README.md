# I am Gabriel Gerhardt.

## About Me
- Backend Developer
- Software Engineering student at PUCRS
- Passionate about building web projects with scalability and real-world impact
- Obsessed with software design patterns, Microservices, and Architecture

## Projects

### Webhook-Manager
- **Java 21 (Spring Boot) + Oracle / PostgreSQL**
- Centralized pub/sub hub that decouples producers from consumers — services emit named events without knowing who's listening
- Fans out payloads to every URL subscribed to a triggered event
- Multi-module design: separate producer, consumer, and manager services
- [Repository](https://github.com/Gabriel-Gerhardt/Webhook-Manager)


### GitCrawler
- **Go 1.22**
- REST API that clones GitHub repos and extracts file data for ingestion
- Deployed with CI and hourly health checks
- Exports in multiple formats (JSON, CSV, XML, HTML) and generates AI summaries of a repo's purpose and stack
- [Repository](https://github.com/Gabriel-Gerhardt/GitCrawler.git)

### ElasticPom
- **Java 21 (Spring Boot) + SvelteKit + Python 3 + MongoDB + Elasticsearch**
- Hybrid search engine for scientific papers: runs **BM25 and vector/kNN independently, then fuses them with Reciprocal Rank Fusion**
- Query embeddings generated locally so they share the ingested corpus's vector space
- Full pipeline: Python ingestion (OAI-PMH) → MongoDB + Elasticsearch → Spring Boot API → SvelteKit UI
- [Repository](https://github.com/Gabriel-Gerhardt/ElasticPom)

## Open Source Contributions
- **Spring Framework** — [PR #37152](https://github.com/spring-projects/spring-framework/pull/37152): fixed broken internal xref links across the reference docs, reviewed and merged by core maintainer Sam Brannen.

## Technologies I Know:
<div style="display: flex; gap: 10px;">

<img height="50px" width="50px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/java/java-original-wordmark.svg" />
<img height="50px" width="50px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/spring/spring-original.svg" />
<img height="50px" width="50px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-plain-wordmark.svg" />
<img height="50px" width="50px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/go/go-original.svg" />
<img height="50px" width="50px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postgresql/postgresql-original.svg" />
<img height="50px" width="50px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/unifiedmodelinglanguage/unifiedmodelinglanguage-original-wordmark.svg" />
<img height="50px" width="50px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/docker/docker-original-wordmark.svg" />
<img height="50px" width="50px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/apachekafka/apachekafka-original-wordmark.svg" />
<img height="50px" width="50px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/elasticsearch/elasticsearch-original.svg" />
<img height="50px" width="50px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" />
<img height="50px" width="50px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/gradle/gradle-original.svg" />
<img height="50px" width="50px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mongodb/mongodb-original-wordmark.svg" />
<img height="50px" width="50px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/oracle/oracle-original.svg" />
<img height="50px" width="50px" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/redis/redis-original-wordmark.svg" />

</div>

## Top Languages
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Gabriel-Gerhardt)

## Contact
- [LinkedIn](https://www.linkedin.com/in/gabriel-gerhardt-0a8b852b9/)
- [Gmail](mailto:gabrielgerhardt27@gmail.com)
- [GitHub](https://github.com/Gabriel-Gerhardt)

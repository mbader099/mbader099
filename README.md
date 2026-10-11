### Hi, I'm Muhana 👋

I build **web crawlers and the data pipelines that turn what they collect into clean,
training-ready datasets**. I also have hands-on **cloud infrastructure** experience: AWS,
Terraform and CI/CD. Computer Science, George Mason University.

#### What I've built

**🕷️ [youtube-creator-crawler](https://github.com/mbader099/youtube-creator-crawler)**: a polite web crawler plus an ML training-data pipeline (personal side project)
- Queue-based BFS over YouTube's recommendation graph, with circuit breakers, `robots.txt`, per-host pacing and `retry-after` backoff
- HTML extraction (trafilatura), exact + **MinHash/LSH near-dedup**, quality and language filtering, PII scrubbing
- Real run: **3,151 crawled docs → 2,096 clean records (~936k tokens)**. Near-dedup caught 69 duplicates that exact matching missed.
- Fine-tuned `distilgpt2` on the output: **held-out perplexity 52 → 38**. CI on Python 3.10 and 3.13.

**☁️ [three-tier-fargate-jenkins-cicd](https://github.com/mbader099/three-tier-fargate-jenkins-cicd)**: a React and Express app, containerized with Docker, deployed to **AWS ECS Fargate** behind an Application Load Balancer, provisioned with **Terraform** and shipped through a **Jenkins** CI/CD pipeline

**🏗️ [terraform-ansible-aws](https://github.com/mbader099/terraform-ansible-aws)**: **Terraform** provisions EC2, S3, IAM and security groups and generates the **Ansible** inventory; Ansible configures and serves the site

**📅 [DMV-Scheduler](https://github.com/mbader099/DMV-Scheduler)**: a team project that scrapes DMV appointment availability with Selenium and serves it through Flask (my first scraper)

#### Toolbox

**Crawling & data:** Python · Playwright · Selenium · trafilatura · datasketch (MinHash/LSH) · langdetect<br/>
**ML:** PyTorch · Hugging Face Transformers & Datasets<br/>
**Cloud & DevOps:** AWS (ECS Fargate, EC2, S3, IAM, ALB) · Terraform · Ansible · Docker · Jenkins · GitHub Actions<br/>
**Earlier:** Solidity · Hardhat · React ([NFT marketplace](https://github.com/mbader099/NFT-Market))

#### Currently

Looking for engineering roles in Cloud and working on **web-scale data for ML**: crawling, extraction, deduplication, data quality.

💼 [LinkedIn](https://www.linkedin.com/in/your-profile)

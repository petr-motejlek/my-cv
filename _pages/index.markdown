---
permalink: /
layout: default
title: Curriculum Vitae
---

{::options parse_block_html="true" /}

<div class="block">

<div class="block-head">

# Petr Motejlek

</div>

<div></div>

- e-mail petr@motejlek.net
- [Petr Motejlek on LinkedIn](http://linkedin.com/in/petr-motejlek-910a9773)

</div>

<div class="block">

<div class="block-head">

## Table of Contents

</div>

- [What I&nbsp;Am Offering](#offering)
- [What I&nbsp;Can Help You With](#next-challenge)
- [I&nbsp;Enjoy Doing, Know About and Am Highly Motivated By](#enjoy-doing)
- [Professional History](#professional-history)


</div>

<div class="block">

<div class="block-head">

## What I&nbsp;Am Offering {#offering}

</div>

- __18+ years of experience__ spanning software development for a plethora
  of platforms, network administration and maintenance, full stack web
  and application development, single machine setups as well as clusters and clouds.
  I also have experience talking to customers, and am able to proficiently understand
  their problems and propose appropriate solutions.  
- Very __quick learner__, preferring __diving deep__, rather than
  superficial understanding.
- Knowledge about __multiple different programming languages and paradigms__
  (currently, my favorites are __TypeScript__ (both NodeJS and browser), __OOP__, __TDD__ and __DDD__
  with a sprinkle of __functional programming__), as well as __automated operationalization__,
  __deployment__, __monitoring__ and __backup__ solutions and strategies, both __on-prem__ and __in-cloud__.
- I __truly enjoy this field__, and always do my best to get better at it.

</div>

<div class="block">

<div class="block-head">

## What I&nbsp;Can Help You With {#next-challenge}

</div>

- __Help you move into the cloud__.
  - If you are there already, I can __help you get better at it__.
- If you need (help) __writing infrastructure as code__, I can assist.
- If you are out of ideas, __I can come up with them__; or I can let you bounce
  them off me, __give you feedback__, and we can __improve them together__.
- I can do __proof-of-concept work__ for you, either in your environment, or in
  my own.
- I can __teach you what I know__.
- No matter the size or scope of the project, let's get in touch. __I am
  certain I can help__.

</div>

<div class="block">

<div class="block-head">

## I&nbsp;Enjoy Doing, Know About and Am Highly Motivated By {#enjoy-doing}

</div>

- __Agile__, __open__, __transparent__ and __trusting__ environment where
  teams are __empowered__ to come up with solutions to problems __on their
  own__. No long-winded requirement specification or design documents written
  by "somebody else" for the teams to "implement without thinking".
- __Automation and clouds__, with __continuous integration__ and __deployment__
  - I want us to deploy our software ourselves (__DevOps is a must__).
- __TypeScript__, __Kubernetes__, __Docker__, __Python__, __Ansible__,
  __IntelliJ IDEA__, __VS Code__, __Scrum__, __AWS__, __Azure__, __Git__,
  etc.
- __Iterative development__ with __short release cycles__.
- __Typing the code__ (hence TypeScript).
- __Clean code__, __clean architecture__.
- Prefer __software over hardware__.
- Prefer working on/with web and media technologies, or related.
- __Transparency__ and __openness__.
- __Sharing__ what I know with others (verbally, through lectures, by
  compiling [knowledge bases](https://bit.ly/my-knowledge-base)).
- __Learning__ more and more.
- Drive for __continuously inspecting and adapting__ on all levels of the
  organization.
- __Flat organization__ with high-performing teams organized around projects
  with full support, responsibility and accountability.
- Experience with __leading teams__ (empowering them to work better and better,
  while developing team members), some experience with being a Product Owner
  and Scrum Master, however prefer being a highly engaged member of a development
  team.
- I prefer a __remote-first work__ (home-office) mode, with the ability
  to go to the ofice in person, as needed.

</div>

<div class="block">

<div class="block-head">

## Professional History {#professional-history}

</div>

<div>

- Too much to all fit here. There's a lot I know already, and what I don't know,
  am always willing to learn, if it helps us grow and deliver better solutions.
- For those who care, there is a list of random keywords at the bottom.

### 2021-present: DevOps Engineer at Trustsoft

* DevOps enginner/architect, mainly focused on helping our clients migrate their on-prem
  solutions into Amazon Web Services' public cloud, no matter the shape or size.
* Daily use of __Terraform__, __Ansible__, __GitOps__, __AWS__,
  __microservices__ (AWS ECS/EKS or EC2 w/ k8s), __Graphana__.

#### Project: Migration of a job-portal company into AWS

* Help our customer migrate from on-prem into AWS by being part of their
platform infrastructure team -- other internal teams utilizing our tools to
migrate their applications into AWS.
* Stack:
  * AWS RDS for PostgreSQL and AWS Aurora for PostgreSQL
  * AWS Transit Gateway and friends
  * ...
  * deployed and managed via AWS CDK (in TypeScript)

#### Project: Migration of a watch and jewelry maker into AWS

* Help our customer design, build and maintain a global environment in AWS,
moving all their on-prem workloads there.
* Customer wanted for their staff to learn from us; a big part of our
responsibility was to teach them along the way. I personally taught their
network team to use Terraform and Terragrunt w/ AWS services.
* Stack:
  * AWS Control Tower
  * AWS Transit Gateway (multi-region)
    * inter-connecting 10's of accounts
    * Next Generation Firewall for east-west and north-south inspection
    * shared egress and ingress (utilizing an SDWAN solution)
  * deployed and managed via Terragrunt&Terraform thru GitHub Actions

#### Project: Migration of a bank into AWS

* Help our customer migrate from on-prem into AWS by being part of their
tooling team -- other internal teams utilizing our tools to migrate their
applications into AWS.
* Stack:
    * AWS CloudFormation, includign Serverless extensions and Macros
    * AWS Service Catalog
    * deployment of the stacks orchestrated by an internally developed tool

#### Project: Migration of card-payment provider into AWS

* Migrate our customer's on-prem card-payment solution from on-prem into AWS
(including design and architecture of the new solution).
* Stack:
  * AWS Transit Gateway, Site-to-Site VPNs, ...
  * AWS ECS w/ Fargate and EC2 instances
  * AWS Aurora for PostgreSQL
  * custom EC2 tooling around HAProxy and StrongSwan to facilitate
  special-needs VPNs
  * deployed and managed via Terraform

#### Project: Migration of card-payment provider's database into AWS

* Migrate our customer's on-prem Oracle database into AWS-hosted PostgreSQL, w/
double-region high-availability. Teach our customer's staff how to operate the
solution.
* Stack:
  * AWS Schema Conversion Tool
  * AWS Database Migration Service
  * AWS RDS for Oracle
  * AWS RDS for PostgreSQL
    * using `pglogical`, `pg_partman`, `pg_cron`, ...
  * multiple custom `plpgsql` scripts to clean up the resulting schema created
  by AWS Schema Conversion Tool
  * deployed and managed via Terraform

### 2021-2021: Full Stack Developer at Pipedrive
	
* Full-stack development of one of Pipedrive parts, leads (we enable our customers to 
better acquire new leads through chatbots, webforms, ...).
* The stack is TypeScript+NodeJS microservice on the backend and TypeScript+React on
  the frontend, both running on top of Kubernetes.
	
### 2019-2020: Software Development Engineer at Akamai

* Full-stack development of a feature enablement service that protomoted DevOps culture
  across engineering groups at Akamai.
* The first version of the product that allowed running an A/B test on Akamai's
  platform done in 2 weeks.
* I particularly enjoyed the vision of being able to directly enable developers
  of features to enable them also.
* Combination of __Python__, __GraphQL__ (__Graphene__), __PostgreSQL__,
  __TypeScript__, __Vue+Vuetify__.

### 2015-2019: Engineering Manager at Akamai

* Lead 8+ engineers spread across two scrum teams.
* Besides __servant-leading__, being involved in one team as a scrum master, also
  __ran an agile evangelization group__ within Akamai.
* Daily experience with __Scrum__, __Kanban__, __JIRA__.
* Created, hosted and contributed regularly to several in-house __knowledge
  sharing sessions__ and online spaces.

### 2014-2015: Lead Software Development Engineer in Test at Akamai

* Lead a team of 5+ engineers. Still participated in the team day to day work as contributor.
* Daily use of __Git__, __TypeScript__, __Python__ and __Java__ (Android development)
  when writing a headless tool (interface) for testing of a multi-platform
  network-protocol library.

### 2013-2014: Software Development Engineer in Test at Akamai

* Work revolving around manual and automated testing of software (dealing with
  web-related protocols, such as __HTTPS__, __TCP__, __UDP__, etc).
	* Experience with __functional__, __white box__, __system__ and __acceptance
          testing__.
	* Design of test cases based on requirement specifications, design
          documents and communication with the development team.
	* Daily usage of __Linux__, __Wireshark__, __tcpdump__, __Bugzilla__,
          __Perforce__, etc.
	* Heavy scripting in __Bash__ and __Python__.

### 2012-2013: Solution Integration Engineer at Gemalto

* Work revolving around buildout and maintenance of server systems deployed with Gemalto software and used by their customers; mainly mobile network operators.
	* Experience with mobile network operators, SIM (smart) cards, etc.

### 2011-2012: Senior Linux/Unix Administrator at Ignum

* Work revolving around network infrastructure and administration of Linux/Unix servers for both customer and internal usage, as well as some Windows Server administration.
* Created and maintained a solution for complete unattended installation of a new server.
	* Experience with CentOS, Kickstart, PXE, etc.
* Day to day work also involved responding to direct customer inquiries and assisting sales people.

### 2007-present: Freelance Consulting and Development

- Work revolving around business-to-business and business-to-customer systems (e.g. e-commerce sites) and network administration; assisting the leadership team in making decisions related to IT.
- Created and maintained a complete network infrastructure for a small business (~ 30 employees) using Windows desktops and Linux servers.
	- Experience with unattended installation of Windows desktops, NT4-style Domains using Samba as well as Active Directory.
	- Experience with running server-side and client-side appliances in VirtualBox, KVM and HyperV.
- Created and maintained an e-commerce site for end customers.
	- Experience with full-stack development of web applications using PHP (Nette, Dibi, etc).
- Created and maintained an e-commerce site for wholesale business partners.
	- Experience with full-stack development of web applications using PHP (Nette, Dibi, etc).

### Certifications

[My Credly Profile Page](https://www.credly.com/users/petr-motejlek/edit)

### Keywords

In no particular order: PHP, Netty, Dibi, Doctrine, Pascal, Delphi, PL/SQL, SQL, Perl, Java, JavaScript (NodeJS and browser), TypeScript, GraphQL, Vue, Vuetify, Python, Bash, Powershell, Linux, Windows, MacOS, Kubernetes, Rancher, Docker, Ansible, PostgreSQL, IntelliJ, VS Code, Git, Garden, Skaffold, Helm, Terraform, HTML, CSS, HTTPS, SSL, Scrum, Kanban, agile, TDD, OO, DDD, functional programming, AWS, Azure, ...

</div>

</div>

Data Engineering has become a discipline based on the **interoperation** of different tools to meet business goals. In order to do so, a data engineer must be aware of various options for tools, their interplay, and their trade-offs.

Nowadays, because of the high levels of abstractions and simplification available, tools are less complicated to manage and deploy, allowing engineers to choose the most effective services that deliver the highest value to the business, by optimizing: cost, reuse, agility, scalability, simplicity, and interoperability.

___

### Skills

"A common curriculum doesn't exist. [...] By definition, a data engineer must understand both data and technology." - *Reis, J 2022, Fundamentals of Data Engineering, O'Reilly Media*

A skill that most engineers take for granted is understanding the implications of data across the organization and the requirements made by data consumers. Data engineers should consider **business** and **technical** perspective when visualizing their responsibilities.

___

### Business Responsabilities

- Communicate with nontechnical and technical people, in order to identify silos.
- Know what to build by developing a sense of how data and technology decisions impact business.
- Ensure a culture that allows Agile, DevOps, and DataOps practices to exist.
- Control costs, often by monitoring it.
- Learn continuously.

As mentioned earlier, a data engineer must understand the big picture and how to deliver value to the business. This work is usually entrusted to managers and tech leaders, but ideally everyone should know about it.

Knowing how to scope and gather requirements, control costs, and constantly learning will set you apart from data engineers who rely solely on their technical abilities.

### Technical Responsabilities

Understand how to build a good [[Data Architecture]] that optimize performance and cost at a high level. Have production-grade software engineering skills. And for programming languages:

- SQL, considered the "lingua franca" of data.
- Python, as is the bridge between data engineering and data science, also frequently used in a lot of APIs for interfacing frameworks.
- JVM languages, such as Java and Scala.
- bash, to improve productivity when performing OS operations .

Competent data engineers should be proficient in SQL, as it quickly solves complex analytics and data transformations problems, and may also need to develop proficiency in secondary programming languages, including R, JavaScript, Go, Rust, C/C++, C#, and Julia.

The most important I think is to focus on fundamentals, beacuse those rarely change over time.

Data engineers don’t all do the same type of work or have the same skill set, in fact, we can group them in two types:

- Type A (*abstraction*): keeps the architecture as simple and abstract as possible, avoiding to reinvent the wheel. They do this by using off-the-shelf products, and managed services/tools.
- Type B (*build*): builds custom data tools and *in-house* solutions, often found in companies that are Scaling or Leading when it comes to [[Maturity]].

___

### Directions

- External: an external-facing data engineer is responsible for architecting, building, and managing systems that collects, stores, and process data from these applications and then return it, as in a feedback loop.
- Internal: at the other side of the spectrum, an internal-facing data engineer focuses on the needs of the business and internal stakeholders. 

These two can blend together, with internal-facing data usually being a prerequisite to external-facing data.

___

### Interactions

As the [[Data Engineering Lifecycle]] cuts across many domains within an organization, the data engineer turns out to be a hub between *data producers* (software engineers, SREs, ...) and *data consumers* (data analysts, data scientists, ...). These two groups can be defined as **Upstream** and **Downstream** stakeholders.

#### Upstream

Understanding the source systems that produce data, as well as the architecture you're using, is crucial to being successful as a data engineer.

A data engineer must work closely with software engineers to understand how source applications (which generate data) work. They are the ones who can dictate the volume, frequency, and format of the generated data, and anything else that will impact the data engineering lifecycle, such as data security and regulatory compliance.

#### Downstream

Data engineers should work closely with downstream users for the same principle as with the upstream users, to get context.

Without data engineering, most of the work done by downstream users could not be accomplish. For example, data engineers ideally should be the ones responsible for enabling data scientists a path to production, and work to provide automations that makes data science more efficient.

Data analysts' expertise on subjects are valuable for improving data quality, and they can also collaborate with data engineers to build pipelines for new data sources required by the business.

#### Leadership

Data engineers often operate in a nontechnical capacity, participating in strategic planning and leading key initiatives that extend beyond the boundaries of IT.




[![Docs](https://img.shields.io/badge/docs-latest-brightgreen.svg)](http://doc.servertribe.com)
[![Discord](https://img.shields.io/discord/844971127703994369)](http://discord.servertribe.com)
[![Docs](https://img.shields.io/badge/videos-watch-brightgreen.svg)](https://www.youtube.com/@servertribe)
[![Generic badge](https://img.shields.io/badge/download-latest-brightgreen.svg)](https://www.servertribe.com/community-edition/)

# Set Up Replication in MySQL






# Attune

[Attune](https://www.servertribe.com/)
automates and orchestrates processes to streamline deployments, scaling,
migrations, and management of your systems. The Attune platform is building a
community of sharable automated and orchestrated processes.

You can leverage the publicly available orchestrated blueprints to increase
your productivity, and accelerate the delivery of your projects. You can
open-source your own work and improve existing community orchestrated projects.

## Get Started with Attune, Download NOW!

The **Attune Community Edition** can be
[downloaded](https://www.servertribe.com/comunity-edition/)
for free from our
[ServerTribe website](https://www.servertribe.com/comunity-edition/).
You can learn more about Attune through
[ServerTribe's YouTube Channel](https://www.youtube.com/@servertribe).







# Clone this Project

Clone this project into your own instance of Attune.

<img src="https://www.servertribe.com/wp-content/uploads/2023/02/Attune-clone-new-project-01.png" alt="clone a new project"/>

---

Paste the GIT repository URL into Attune and Select Clone.

<img src="https://www.servertribe.com/wp-content/uploads/2023/02/Attune-clone-new-project-02.png" alt="clone a new project"/>

---

**Now that this project is in your Attune instance you can begin creating
Jobs.**

Navigate to the Plan workspace and create a Job from a Blueprint in the
Project you cloned.

<img src="https://www.servertribe.com/wp-content/uploads/2023/02/Attune-plan-new-job-11.png" alt="plan a new job"/>

---

Configure the Parameters for the Job you created. Create the Values you're
missing in the next step.

<img src="https://www.servertribe.com/wp-content/uploads/2023/02/Attune-plan-new-job-12.png" alt="plan a new job"/>

---

Create the Values required to fill the Parameters for the Job.

<img src="https://www.servertribe.com/wp-content/uploads/2023/02/Attune-plan-new-job-13-1.png" alt="plan a new job"/>

---

Run your Job.

<img src="https://www.servertribe.com/wp-content/uploads/2023/02/Attune-run-job-01.png" alt="run your job"/>

---

**Congratulations, you’ve run a cloned project.**

If you need further assistance, please explore our help.

<img width=200 src="https://www.servertribe.com/wp-content/uploads/2023/02/Attune-get-help-01.png" alt="get help"/>




## Blueprints

This Project contains the following Blueprints.



### Configure MySQL Group Replication


### Configure MySQL Replica Server for Replication


### Configure MySQL Source Server for Replication


### Start MySQL Group Replication


### Test MySQL Database Replication





## Parameters


| Name | Type | Script Reference | Comment |
| ---- | ---- | ---------------- | ------- |
| Binary Log File | Text | `binarylogfile` | This defines the base name and location of MySQL's binary log file. Example: "/var/log/mysql/mysql-bin.log" |
| Database to Replicate | Text | `databasetoreplicate` | The name of the database you want to replicate. |
| MySQL Group Servers | Node List | `mysqlgroupservers` | None |
| MySQL Group UUID | Text | `mysqlgroupuuid` | Generate a UUID that we can use to identify the MySQL group we will be creating. On the first member of the group, use the command `uuidgen` command to generate a valid UUID for the group. |
| MySQL Instance server-id | Text | `mysqlinstanceserverid` | The server-id directive, which defines an identifier that MySQL uses internally to distinguish servers in a replication setup. Every server in a replication environment, including the source and all its replicas, must have their own unique server-id value. |
| MySQL Node | Linux/Unix Node | `mysqlnode` | None |
| MySQL Replica Node | Linux/Unix Node | `mysqlreplicanode` | The node replicating the source database. |
| MySQL Replica Servers | Node List | `mysqlreplicaservers` | The list of replica nodes. |
| MySQL Replica User | Basic Credential | `mysqlreplicauser` | MySQL Replica User account for replica nodes to connect to the source MySQL instance. |
| MySQL Source Log File | Text | `mysqlsourcelogfile` | None |
| MySQL Source Log Position | Text | `mysqlsourcelogposition` | None |
| MySQL Source Node | Linux/Unix Node | `mysqlsourcenode` | The node containing the source database. |
| Relay Log File | Text | `relaylogfile` | The location of the replica’s relay log file. Example: "/var/log/mysql/mysql-relay-bin.log" |
| root User | Linux/Unix Credential | `rootuser` | Linux root user credentials. |




## Files


| Name | Type | Comment |
| ---- | ---- | ------- |






# Contribute to this Project

**The collective power of a community of talented individuals working in
concert delivers not only more ideas, but quicker development and
troubleshooting when issues arise.**

If you’d like to contribute and help improve these projects, please fork our
repository, commit your changes in Attune, push you changes, and create a
pull request.

<img src="https://www.servertribe.com/wp-content/uploads/2023/02/Attune-pull-request-01.png" alt="pull request"/>

---

Please feel free to raise any issues or questions you have.

<img src="https://www.servertribe.com/wp-content/uploads/2023/02/Attune-get-help-02.png" alt="create an issue"/>


---

**Thank you**

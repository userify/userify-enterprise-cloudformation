# Enterprise Cluster Cloudformation Template

![Diagram](diagram.png "Template Resources")

Also, a build.sh script which automates template builds (with some rudimentary output, although watching the events tab in the console is better).

This template depends on a virtualenv tarball at releases.userify.com (referenced within the template), but the only thing needed to try it out is to launch it in CloudFormation in the AWS console or at the command line.

Important: this template has only been lightly tested, and only in US-East-1. Additional testing is needed.

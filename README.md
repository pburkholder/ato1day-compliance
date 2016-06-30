ATO in a day
==============

This project is an example of how you can re-use off-the-shelf cloud systems (AWS, in this case) and open-source frameworks, and their accompanying NIST-800-53 controls as described by _opencontrol_ to rapidly generate a complete system security plan (SSP)

As this project is in a state of flux, current documentation is in the
[wiki](https://github.com/pburkholder/ato1day-compliance/wiki)

Outline
- freedonia-aws-compliance
  - development Terraform one node with SSH to [ips] and port 80 to [ips]
  - production: Terraform one node with SSH to [ips] and port 80 to 0.0.0.0
  - provision w/ Chef

- freedonia-compliance-compliance
  - build exports
  - push to S3
  - publish on gitbook server

 Audience
 - FISMA newbies that need a getting started
 - FISMA experts that need a more efficent way of doing work
 - FISMA enforcers that need to trust the framwework we're presenting

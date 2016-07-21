# codeswitch.mn

URL: http://codeswitch.opentwincities.org

This repository is for technical documentation related to the Code Switch website.

## Stack

Codeswitch.mn is a Wordpress site hosted on AWS using a [Bitnami](https://aws.amazon.com/marketplace/pp/B007ALICSY) image that setup a LAMP stack. The [introductory reference page for Bitnami is available here](http://codeswitch.opentwincities.org/bitnami/index.html).

## SSH

Assuming you have a key setup, simply `ssh bitnami@codeswitch.opentwincities.org` .

## phpMyAdmin

phpMyAdmin is available, but only via tunneled access to `http://127.0.0.1/phpmyadmin` . [See these instructions on how to access phpMyAdmin](https://wiki.bitnami.com/Components/phpMyAdmin#How_to_enable_phpMyAdmin_or_phpPgAdmin_to_be_accessed_remotely.3f).

## Snapshots

A snapshot of the EC2 instance's root value is captured daily.

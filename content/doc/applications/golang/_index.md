---
type: docs
title: Go
shortdesc: Go, otherwise known as Golang, is an open source, compiled, garbage-collected, concurrent system programming language.
tags:
- deploy
keywords:
- go
- golang
str_replace_dict:
  "@application-type@": "Go"
type: docs
aliases:
- /doc/deploy/application/golang
- /doc/deploy/application/golang/go
- /doc/getting-started/by-language/go
- /doc/partials/language-specific-deploy/go
---

## Overview

Clever Cloud allows you to deploy any Go application. This page will explain you how to set up your project to run it on our service. You won't not need to change a lot, the *requirements* will help you configure your applications with some mandatory files to add, and properties to setup.

{{< readfile file="create-application.md" >}}

{{< readfile file="set-env-vars.md" >}}

{{< readfile file="language-specific-deploy/go.md" >}}

{{< readfile file="deploy-git.md" >}}

{{< readfile file="link-addon.md" >}}

{{< readfile file="more-config.md" >}}

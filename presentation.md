<script>
  addEventListener("load", (event) => {
    for (const el of document.querySelectorAll('[contenteditable]')) {
      el.addEventListener('keydown', e => e.stopPropagation());
    }
  });
</script>

# Introducing Snyk

#### Maciej Barelkowski

---

## Goals:

* 🤔 Understand why we use Snyk
* 🏎 Find out what we can achieve with Snyk
* 🏗 Learn how we use or can use the platform

---

## Why do we care about software security?

# *Share your thoughts!*

<ol>
  <li contenteditable="true"></li>
  <li contenteditable="true"></li>
  <li contenteditable="true"></li>
</ol>

<!--
* pass certification
* ethics
* own satisfaction
*
* build and maintain trust
 -->

---

## What is Snyk?

#### Code security tool which helps to detect and fix vulnerabilities.

### Tool which helps to *achieve software security*.

---

## Key features

* Scan dependencies
* Scan source code
* Scan Docker images

---

## Dependencies scanning

* Detects more than npm audit, e.g. [#305](https://github.com/camunda-community-hub/zeebe-client-node-js/pull/305).
* Scans production deps only per default (no usual npm audit hassle!).

---

## Code scanning a.k.a. Snyk Code

* Analyze source code for potential vulnerabilities, e.g. [#3475](https://github.com/camunda/camunda-modeler/pull/3475)

---

## Docker images scanning

* Useful for most teams at Camunda.

---

## Getting started

* Confluence section: https://confluence.camunda.com/x/7Id2Bg
  * Includes links to Snyk documentation
* Let's have a look at the tool: https://app.snyk.io/

---

## Next steps

* Create a team
* Add projects with lifecycle *production*
* Own the tool

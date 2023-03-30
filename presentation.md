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

* Understand why we use Snyk
* Find out what we can achieve with Snyk
* Learn how to use the platform

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

---

## What is Snyk?

#### Code security tool which helps to detect and fix vulnerabilities.

---

## What is Snyk?

#### Code security tool which helps to detect and fix vulnerabilities.

### Tool which helps to *achieve software security*.

---

## Key features

* Scan dependencies (also in Docker images) for known vulnerabilities
* Verify dependencies licenses
* Scan source code for potential vulnerabilities

---

## Dependencies scanning

* Detect more than npm audit, e.g. [#305](https://github.com/camunda-community-hub/zeebe-client-node-js/pull/305).
* Scan production deps only per default (no usual npm audit hassle!).
* Scan Docker images as well.

---

## License scanning

* Ensure license compliance
* Prevent accidental usage of copyleft dependencies

---

## Code scanning a.k.a. Snyk Code

* Analyze source code for potential vulnerabilities, e.g. [#3475](https://github.com/camunda/camunda-modeler/pull/3475)
* Detect risky code and learn about vulnerabilities

---

## Getting started

* Confluence section: https://confluence.camunda.com/x/7Id2Bg
  * Includes links to Snyk documentation
* Let's have a look at the tool: https://app.snyk.io/

<!--
* dashboard view
* add a project with lifecycle production
* ignoring reports
* setup notifications
-->

---

## Next steps

* Create a team
* Add projects
* Use the tool

Potentially:

* CI integration: [Snyk Node action](https://docs.snyk.io/integrations/ci-cd-integrations/github-actions-integration/snyk-node-action)
* Security policy as code: [.snyk file](https://docs.snyk.io/snyk-cli/test-for-vulnerabilities/the-.snyk-file)

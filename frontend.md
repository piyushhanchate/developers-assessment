# Frontend Assessment: WorkLog Payment Dashboard

## Background

You're building an **admin dashboard for a company that hires freelancers**. Freelancers log their time against tasks, and at the end of each payment cycle, an admin reviews the logged work and processes payments.

Each task has a **worklog** containing multiple **time entries** recorded by the freelancer. The admin needs to review the logged work, decide what should be paid for, and issue payments.

For this assessment, you will **build only the frontend interface**. Instead of connecting to a real backend, you will use **mock JSON data** to simulate API responses.

---

## Requirements

1. Admin should see a **list of all worklogs with total earnings per task**
2. Admin should be able to **drill down into a worklog to see individual time entries**
3. Admin should be able to **filter worklogs by a date range** to determine which are eligible for payment
4. Admin should be able to **review the selected worklogs before confirming payment**
5. Admin should be able to **exclude specific worklogs or freelancers from a payment batch**

---

## Implementation Guidelines

* Build a **frontend-only implementation**.
* Use **mock JSON data** to simulate backend responses for:

  * Worklogs
  * Time entries
  * Freelancer information
  * Payment summaries
* Mock data can be stored:

  * in local JSON files, or
  * in a small mock data layer/service in the frontend.

You may structure the mock data however you see fit, but it should resemble realistic API responses.

---

## Suggested Stack

You may use the following stack - which is already setup:

* **Next.js**
* **React**
* **TypeScript**
* Any UI library of your choice (optional)

---

## Required Documentation

Your PR must include:

### a. Screenshots

Include screenshots of the key screens in your implementation. Examples include:

* Worklogs list view
* Worklog details / time entries view
* Date range filtering
* Payment review screen

Include them in the PR description.

---

## Submission Checklist

* [ ] Functional frontend implementing the required workflows
* [ ] Uses mock JSON data instead of a backend
* [ ] Clear component structure and code organization
* [ ] Added screenshots of relevant screens
* [ ] Created Pull Request

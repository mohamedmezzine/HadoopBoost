# HadoopBoost

Responsive static website for a Big Data / Hadoop service concept.

## Overview

HadoopBoost is a front-end web project presenting a Big Data service platform. The website is built around Hadoop-related consulting and infrastructure services: secure cluster deployment, data analytics, operational optimization, real-time decision support, and customer-experience improvement.

The project is a static website prototype. It does not include a Hadoop backend or data-processing engine.

## Project Goal

The goal is to build a clean company website for a Hadoop / Big Data solution provider. The website focuses on:

- presenting services clearly;
- explaining the business value of Big Data;
- offering pricing plans;
- creating a consultation/contact flow;
- adapting a Bootstrap template into a domain-specific website.

## Main Features

- Responsive landing page
- Navigation menu with pages for About, Services, Blog, Pricing, Team, Testimonials, Quote, and Contact
- Hero carousel introducing the Big Data value proposition
- Service cards for security, analytics, operations optimization, decision support, and customer experience
- Pricing plan section with storage and processing capacity examples
- Consultation call-to-action
- Contact information and social links
- Bootstrap-based visual layout
- Font Awesome and Bootstrap Icons integration
- Animation and carousel libraries

## Repository Structure

```text
.
├── hadoopboostwebpage/
│   └── startup-website-template/
│       ├── index.html
│       ├── about.html
│       ├── service.html
│       ├── price.html
│       ├── contact.html
│       ├── quote.html
│       ├── css/
│       ├── js/
│       ├── lib/
│       └── img/
└── README.md
```

## Tech Stack

- HTML5
- CSS3
- Bootstrap
- JavaScript
- Font Awesome
- Bootstrap Icons
- Owl Carousel
- Animate.css / WOW.js-style animations

## How to Run Locally

### Option 1: Open directly

Open this file in your browser:

```text
hadoopboostwebpage/startup-website-template/index.html
```

### Option 2: Run with a local server

From inside the template folder:

```bash
cd hadoopboostwebpage/startup-website-template
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Notes

- Some pages still mix English and French content.
- Contact forms and quote forms are static unless connected to a backend.
- Pricing examples are illustrative and not linked to billing logic.

title: Prometheus and OpenTelemetry
---

## Overview
Prometheus and OpenTelemetry are often used together, but users are frequently confused about their roles and how they interoperate.

## What is Prometheus?
Prometheus is a metrics-based monitoring system that uses a pull-based model to scrape metrics.

## What is OpenTelemetry?
OpenTelemetry provides APIs, SDKs, and tools to generate and manage telemetry data such as metrics, traces, and logs.

## How they work together
A common setup is:

App → OpenTelemetry SDK → OpenTelemetry Collector → Prometheus

## When to use what
- Use Prometheus for metrics storage and alerting
- Use OpenTelemetry for instrumentation and data collection

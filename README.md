# Monitoring Event Simulation – ServiceNow

This project simulates an enterprise monitoring and event management system using ServiceNow.

It demonstrates how external monitoring tools (like Prometheus, Datadog, or CloudWatch) send alerts to ServiceNow, which are processed and converted into actionable incidents.

---

## 🎯 Project Objective

To design a real-time alert ingestion and processing system that:

- Receives monitoring alerts via REST API
- Stores alerts as event records
- Prevents duplicate alerts
- Automatically creates incidents
- Maps severity to priority

---

## ⚙️ Features Implemented

### 1. REST API Integration
- Scripted REST API to receive monitoring alerts
- Accepts JSON payloads

### 2. Event Processing
- Custom event table to store alerts
- Tracks event status (New / Processed)

### 3. Deduplication Logic
- Prevents duplicate alerts using Business Rule
- Ensures system stability during alert storms

### 4. Incident Automation
- Automatically creates incidents from events
- Maps severity to incident priority

---

## 🔄 Data Flow

Monitoring Tool → REST API → Event Table → Business Rule → Incident

---

## 🧪 Demo Scenario

1. Send alert via REST API
2. Event record created
3. Incident automatically generated
4. Duplicate alert is blocked

---

## 🧠 Interview Value

Demonstrates:

- Event-driven architecture
- Monitoring system integration
- Alert deduplication strategies
- Automated incident response
- Real-world DevOps integration patterns

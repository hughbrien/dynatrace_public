# REST Application Performance Report

**Generated:** September 19, 2025  
**Service:** rest-application  
**Entity ID:** SERVICE-D867ED3C821BD14F  
**Analysis Period:** Last 24 hours  
**Environment:** https://uim8926h.sprint.apps.dynatracelabs.com

---

## 📊 Executive Summary

The REST application service has been analyzed for performance metrics over the past 24 hours. **Critical performance issues** have been identified with three primary endpoints showing extremely slow [...]

### Key Findings:
- ✅ **No application errors or exceptions detected**
- 🚨 **3 endpoints with critical performance issues (>3 seconds)**
- ✅ **8 endpoints performing well (<10ms)**
- 📈 **Low traffic volume: ~60 total requests**

---

## 🎯 Service Overview

| Metric | Value |
|--------|-------|
| **Service Name** | rest-application |
| **Entity ID** | SERVICE-D867ED3C821BD14F |
| **Total Endpoints** | 11 active endpoints |
| **Monitoring Period** | 24 hours |
| **Total Requests** | ~60 requests |

---

## ⚡ Performance Analysis

### 🚨 Critical Performance Issues

#### Slowest Endpoints (Response Time Analysis)

| Rank | Endpoint | Avg Response Time | 95th Percentile | Min-Max Range | Requests | Status |
|------|----------|-------------------|-----------------|---------------|----------|---------|
| 1 | `/application` | **4.58 seconds** | **15.42 seconds** | 829ms - 15.4s | 4 | 🔴 Critical |
| 2 | `/greeting` | **4.04 seconds** | **5.22 seconds** | 2.8s - 5.2s | 4 | 🔴 Critical |
| 3 | `/applicationx` | **3.39 seconds** | **4.58 seconds** | 1.99s - 4.49s | 4 | 🔴 Critical |

### ✅ Well-Performing Endpoints

| Endpoint | Avg Response Time | 95th Percentile | Requests | Status |
|----------|-------------------|-----------------|----------|---------|
| `/welcome` | 4.6ms | 7.5ms | 4 | 🟢 Excellent |
| `/check_message` | 4.4ms | 9.0ms | 4 | 🟢 Excellent |
| `/machine` | 7.7ms | 8.6ms | 4 | 🟢 Excellent |

### 🛠️ Test/Error Endpoints (Expected Behavior)

| Endpoint | Avg Response Time | Expected Status | Requests | Performance |
|----------|-------------------|-----------------|----------|-------------|
| `/api/basic/null-error` | 7.8ms | 500 (Expected) | 4 | 🟢 Good |
| `/api/basic/bad-path/{id}` | 6.3ms | 400 (Expected) | 4 | 🟢 Good |
| `/api/basic/divide-by-zero` | 5.0ms | 500 (Expected) | 4 | 🟢 Good |
| `/api/basic/unhandled` | 4.9ms | 500 (Expected) | 4 | 🟢 Good |

---

## 📈 Error Analysis

### HTTP Status Code Distribution

| Status Code | Count | Percentage | Description |
|-------------|-------|------------|-------------|
| **200 OK** | 26 | 65% | Successful requests |
| **500 Internal Server Error** | 12 | 30% | Test endpoints (expected) |
| **400 Bad Request** | 4 | 10% | Test endpoints (expected) |
| **404 Not Found** | 3 | 7.5% | Resource not found |

### Error Rate Analysis
- **Application Error Rate:** 0% (No unexpected errors)
- **Exception Count:** 0 (No unhandled exceptions detected)
- **Test Endpoint Errors:** 100% expected (functioning correctly)

---

## 🔍 Detailed Performance Metrics

### Response Time Distribution

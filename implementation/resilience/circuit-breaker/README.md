# Circuit Breaker

This folder contains circuit breaker pattern implementations for your API.

## Purpose

The circuit breaker module provides:
- Circuit breaker implementations for external service calls
- Configurable failure thresholds and timeout settings
- State management (Open, Closed, Half-Open)
- Monitoring and metrics for circuit breaker states
- Integration examples with common HTTP clients

## How It Works

Circuit breakers prevent cascading failures by:
1. **Closed State**: Normal operation, requests flow through
2. **Open State**: When failures exceed threshold, circuit opens and requests fail fast
3. **Half-Open State**: After timeout, circuit allows test requests to check if service recovered

## Contents

Implementations support various circuit breaker libraries and patterns, allowing teams to protect their APIs from downstream service failures and improve overall system resilience.

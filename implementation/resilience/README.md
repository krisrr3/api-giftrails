# Resilience

This folder contains resilience patterns and fault tolerance implementations for your API.

## Purpose

The resilience module provides:
- **circuit-breaker/** - Circuit breaker patterns to prevent cascade failures
- **fault-tolerance/** - Retry policies, timeouts, and fallback strategies

## Contents

Resilience implementations help APIs gracefully handle failures, degradation, and high-load scenarios, ensuring better availability and user experience even when downstream dependencies experience issues.

## Patterns Included

- Circuit breakers for external service calls
- Retry mechanisms with exponential backoff
- Timeout configurations
- Bulkhead isolation patterns
- Fallback strategies

# Leasing companies – reference definition

This directory defines which leasing companies are included in
Bilpriser.no analyses, dashboards, calculators and APIs.

## Purpose
This list is the canonical source of truth for identifying leasing
companies across all Bilpriser.no services.

## Inclusion criteria
- Offers leasing products in the Norwegian market
- Registered Norwegian organization number
- Relevant for new car registrations and leasing statistics

## Field definitions
- `id`  
  Stable internal identifier. Must never be changed once published.

- `name`  
  Official company name.

- `orgnr`  
  Norwegian organization number (Brønnøysund).

- `active`  
  Whether the company is currently included in standard analyses.

## Change policy
- New companies are added via pull request
- Changes must be documented
- Historical IDs must not be reused


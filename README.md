# hacksprint2026
DukaanScan: Multimodal AI-powered product cataloging and vernacular marketing for Indian small merchants
# DukaanScan
> **From one product photo to a multilingual digital storefront.**
DukaanScan is a multimodal AI-powered commerce assistant designed to help Indian small merchants, artisans, and micro-businesses transform physical products into professional, commerce-ready digital listings.
Built for **HackSprint 2026 — PS42 (Applied AI)**
## The Problem
Small merchants often have great products but face friction when taking them online. Creating a digital listing requires product photography, titles, descriptions, categorization, attributes, tags, and marketing content — often in multiple languages.
This makes digital commerce unnecessarily difficult for merchants with limited time, technical expertise, or access to professional marketing resources.
## Our Solution
DukaanScan transforms a simple product image into a structured digital catalog.
### How it works
**Upload → Understand → Generate → Localize → Export**

1. Merchant uploads product images or a short video.
2. **Google Gemini** analyzes the product and extracts visible attributes.
3. DukaanScan generates a structured product listing.
4. Missing or unverifiable information is flagged for merchant input.
5. **Sarvam AI** generates localized marketing content and regional-language voice ads.
6. Product information can be exported as structured commerce-ready data.

## Key Features

- **Multimodal Product Understanding**
- **Automatic Product Listing Generation**
- **Attribute, Category & Tag Extraction**
- **Missing Information Detection**
- **Vernacular Marketing Content**
- **Regional-Language Voice Ads**
- **Structured Commerce-Ready Export**

## Tech Stack

| Component | Technology |
|---|---|
| Multimodal AI | Google Gemini |
| Cloud | Google Cloud |
| Vernacular AI | Sarvam API |
| Frontend | React / Next.js |
| Backend | Python / FastAPI |
| Database / Analytics | BigQuery |
| Storage | Google Cloud Storage |

## Architecture

Merchant  
↓  
Product Image / Video  
↓  
DukaanScan Web Application  
↓  
Google Gemini — Product Understanding  
↓  
Structured Product Intelligence  
↓  
Catalog Generation  
↓  
Sarvam API — Localization & Voice  
↓  
Commerce-Ready Product Listing

## HackSprint 2026

**Track:** Applied AI  
**Problem Statement:** PS42 — Gemini + Google Cloud

DukaanScan addresses PS42 by using multimodal AI to transform fragmented visual and textual product information into structured, context-aware and actionable commerce data.

## Team
|Sakshi | TBD |
|Aanya | TBD |
|Nethra | TBD |
|Asmi | TBD |

## Project Status
**Prototype under development for HackSprint 2026.**

## Future Scope

- Direct marketplace / ONDC integration
- Batch product cataloging
- Additional Indian languages
- Voice-first merchant interaction
- Merchant analytics
- Data-backed pricing recommendations
- Social media campaign generation

## Responsible AI
DukaanScan distinguishes between visually observable product attributes and information that cannot be reliably inferred from an image. Merchants are prompted to verify generated information before publishing.

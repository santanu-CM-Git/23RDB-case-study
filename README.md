# 23RD Pay Case Study

## About Project

**23RD Pay** is a cross-platform money transfer app (React Native) with a Laravel API and admin panel. Users can send and request money, manage contacts and cards, review transaction history, and complete KYC document uploads. The platform supports multiple payment gateways, push notifications, and offline-aware UX.

## Problem

Consumer fintech products must balance simple peer-to-peer transfers with regulated onboarding — security questions, document verification, and platform fees — while supporting several payment providers and giving operations a single place to configure fees, users, and compliance data. Fragmented mobile and backend stacks increase failed payments, support load, and audit risk.

## Technology Stack

**Mobile:**  
React Native, React, TypeScript, Redux Toolkit, React Navigation, Stripe React Native, Firebase Cloud Messaging

**Backend:**  
Laravel 11, PHP 8.2, Laravel Sanctum, PayPal, Paystack, Stripe

## The Client

A fintech product team building a consumer payment app for peer-to-peer transfers, contact-based payments, and regulated onboarding (security questions, document verification, platform fees).

## The Solution

- **Mobile App:** Auth (login, signup, password recovery), send/request money flows, contact and card management, searchable transaction history, portfolio and exchange rates, document upload, and settings (privacy, terms, about).
- **Backend API:** Sanctum-protected REST endpoints for users, contacts, cards, transactions, and payment intents; public master data (countries, security questions, document types).
- **Admin Panel:** User and transaction oversight, platform fee configuration, security questions, document/identification types, logos, and notification management.
- **Payments & Security:** Multi-gateway checkout (Stripe, PayPal, Braintree, Paystack), token-based API auth, 2FA via security questions, and KYC document workflows.

## Result

- One unified mobile surface for send, request, contacts, cards, and history with offline-aware behavior where it matters.
- Centralized API and admin tooling for users, transactions, fees, and KYC configuration without ad-hoc database edits.
- Flexible checkout across major gateways so users are not locked to a single processor.
- Clear separation of public master data and Sanctum-protected user flows for safer, auditable operations.

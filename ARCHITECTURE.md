# AcreFi Architecture

## Overview

AcreFi is composed of three main layers:

### 1. Protocol layer
Smart contracts responsible for:
- liquidity pools
- loan registration
- repayment tracking
- pool accounting

### 2. Off-chain services
Services responsible for:
- credit analysis
- collateral validation
- borrower verification
- oracle integrations

### 3. Application layer
Frontend interfaces for:
- liquidity providers
- borrowers
- validators
- protocol admins

## Initial modules

### LiquidityPool
Handles:
- deposits
- withdrawals
- pool accounting

### BorrowerVault
Handles:
- borrower profile
- private score references
- collateral registration metadata

### LoanContract
Handles:
- principal
- interest
- repayment schedule
- status tracking

## Initial collateral model
The MVP will focus on:
- agricultural receivables
- milk payment receivables
- short-term productive credit

## Future expansion
- tokenized CPR
- machinery financing
- insurance-linked protection
- governance token

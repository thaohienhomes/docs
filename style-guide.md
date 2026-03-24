---
title: "Pho.Chat Documentation Style Guide"
---

# Pho.Chat Style Guide

This is the single source of truth for all Pho.Chat documentation content.
Referenced by Mintlify Workflows for automated auditing.

## Diátaxis Rules
- Tutorial = "Bắt đầu với X" — for new users
- How-To = "Cách X" — for users who know the basics
- Reference = "Tham khảo X" — quick lookup
- Explanation = "Hiểu về X" — why, how it works
- NEVER mix content types on one page

## Voice
- Friendly, confident, not academic
- Use "bạn" (not "quý khách" or "anh/chị")
- Keep English for: Dashboard, Export, Import, AI, PDF, Settings, Login, Upload, Download
- Translate: Hướng dẫn, Tính năng, Cài đặt, Tài khoản, Bắt đầu
- Never use "đơn giản", "dễ dàng", "chỉ cần"
- Sentences ≤25 words, active voice ≥90%

## Components
- <Steps> for tutorials & how-tos
- <AccordionGroup> for FAQ & troubleshooting
- <CardGroup cols={2}> for feature navigation
- <Tip> before best practices (max 2 per section)
- <Warning> BEFORE dangerous steps
- <Note> for tier restrictions
- <Tabs> for Desktop vs Mobile

## Tier Badges
- 🟢 Free — No badge needed
- 🔵 Pro — <Note>Tính năng này có từ gói **Pro** trở lên.</Note>
- 🟣 Medical — <Note>Tính năng này có từ gói **Medical** trở lên.</Note>
- ⭐ Lifetime — mention in pricing only

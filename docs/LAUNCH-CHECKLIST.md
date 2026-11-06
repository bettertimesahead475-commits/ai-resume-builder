# Launch gates — AI Resume Builder

Status: **NOT LAUNCHED**. Do not accept customer payments until all gates pass.

## Required before public traffic
- [ ] Run CI and test real Cloudflare Worker deployment
- [ ] Add server-side authentication, rate limiting, Turnstile and abuse budgets to generation API
- [ ] Configure AI API secret in Cloudflare (never commit it)
- [ ] Add PDF/DOCX export and verify files render correctly
- [ ] Implement paid order creation and unguessable order IDs
- [ ] Integrate Gmail payment notifications with strict sender validation, amount/reference matching and replay prevention
- [ ] Require manual bank confirmation for ambiguous or unverified e-Transfers
- [ ] Add admin-only approve/refund actions and audit trail
- [ ] Secure customer information: access controls, retention/deletion, privacy policy and consent
- [ ] Test full purchase-to-delivery path with real controlled transactions
- [ ] Connect domain and configure transactional emails

## Rules
- Email notification alone is not conclusive proof that money arrived.
- Do not auto-approve payments based only on text matching.
- No fabricated experience, credentials, dates, or achievements.
- Never put API keys, banking credentials, or customer personal data in GitHub.
- CYFSA Navigator is a separate project and must remain untouched.

### Pull Request Requirements
- Title: `feat: <title>`, `fix: <title>`, etc.
- Description must include:
  - What was done
  - Why it was done
  - Screenshots/logs (if frontend)
  - How to test it
  - Test coverage results
- Linked Issue (if applicable)
- Add reviewers from the core team
- All CI checks must pass

**Any PR that fails CI or has test warnings is auto-closed.**

---

## 🔍 SECURITY AND PRIVACY

- Never log personal or legal data (real or fake)
- Use `.env.example` for all secrets/configs
- Ensure encryption where applicable (AES-256 for files, hashed passwords)

---

## 📚 DOCUMENTATION

You must update relevant documentation if:
- You add/remove an endpoint
- You change file/folder structure
- You alter data schemas or models
- You touch any compliance-related logic

Failing to update docs is grounds for PR rejection.

---

## ⚠️ ABSOLUTE NO-GOs

- Commit secrets, keys, tokens — you’ll be blocked.
- Touching production (`main`) without approval.
- Writing AI prompt logic that hardcodes sensitive legal assumptions.
- Bypassing lint, type, or test checks with `--force` or `--no-verify`.

---

## 📞 NEED HELP?

Ask in the team Slack channel or open a `question` issue. Don’t guess on legal logic or jurisdictional edge cases.

---

Thank you for helping build a secure, scalable, and legally rigorous platform.

— The JurisMind Core Team

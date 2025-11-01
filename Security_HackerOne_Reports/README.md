# HackerOne Bug Findings - Daniel Bates

**Researcher:** Daniel Bates
**Email:** danielalanbates@gmail.com
**Date Started:** October 19, 2025

---

## 📁 This Folder

All vulnerability findings from automated and manual testing are saved here.

**Files:**
- `*.json` - Raw test results and findings
- `*_Report.md` - Professional HackerOne submission reports
- `README.md` - This file

---

## 🎯 Current Findings

### 1. GitLab - Missing Rate Limiting (Medium)
**File:** `GitLab_Missing_Rate_Limiting_Report.md`
**Status:** Ready for submission
**Severity:** Medium
**Bounty Estimate:** $100-$500

**Summary:** GitLab's GraphQL API endpoint doesn't implement rate limiting, allowing unlimited rapid requests.

**Proof:** 20 requests sent in 5 seconds, all succeeded, no throttling.

**Submission URL:** https://hackerone.com/gitlab/reports/new

---

## 🤖 Automated Testing Active

**Worker 8** is continuously testing for bugs every 2 minutes:
- Deep manual testing (authorization bypass, IDOR, DoS)
- Authenticated testing (when token provided)
- Real vulnerability discovery (not just scanning)

**All new findings automatically save to this folder!**

---

## 📊 Statistics

**Total Findings:** 1
**Submitted:** 0
**Accepted:** 0
**Bounties Earned:** $0

*(Will be updated as you submit and get results)*

---

## 🚀 How to Submit

1. **Review the report:** Open the `*_Report.md` file
2. **Verify it's valid:** Make sure the bug is real
3. **Go to HackerOne:** Visit the submission URL in the report
4. **Copy/paste:** Use the markdown content
5. **Submit:** Click submit!

---

## 📝 Next Steps

1. **Submit GitLab rate limiting finding** - It's ready to go!
2. **Wait for Worker 8** - It's finding bugs automatically
3. **Check this folder** - New findings save here every 2 minutes
4. **(Optional) Add GitLab token** - For deeper authenticated testing

---

## ⚠️ Important Notes

**DO:**
- ✅ Review findings before submitting
- ✅ Test manually to verify
- ✅ Submit only valid bugs
- ✅ Follow responsible disclosure

**DON'T:**
- ❌ Submit false positives
- ❌ Use others' API keys
- ❌ Test without permission
- ❌ Spam bug bounty programs

---

## 🎓 What Makes a Good Bug Report

1. **Clear title** - Exact vulnerability type
2. **Impact explanation** - Why it matters
3. **Proof of concept** - Working code/commands
4. **Steps to reproduce** - Exact instructions
5. **Recommended fix** - Show you understand it
6. **Professional tone** - Clear, concise, respectful

---

**Good luck with your bug bounty hunting!** 🐛💰

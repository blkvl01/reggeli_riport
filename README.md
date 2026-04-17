# 📊 HGL Reggeli Riport Dashboard

Python-based automated morning dashboard for HGL Ecommerce team.

## 🌐 Live Dashboard

**https://blkvl01.github.io/reggeli-riport/reggeli_riport.html**

## ⏰ Auto-refresh

Every day at 6:00 AM (Budapest time) via GitHub Actions

## 🔧 Manual Run

1. Go to [Actions](../../actions)
2. Select "Reggeli Riport Dashboard"
3. Click "Run workflow"

## 📁 Files

- `generate_dashboard.py` - Main Python script
- `requirements.txt` - Python dependencies
- `.github/workflows/daily-dashboard.yml` - GitHub Actions automation

## 🔐 SharePoint Auth (Optional)

If files are private, add these secrets in repo Settings → Secrets:

- `SP_TENANT_ID` - Azure AD Tenant ID
- `SP_CLIENT_ID` - App Registration Client ID
- `SP_CLIENT_SECRET` - App Secret

Public SharePoint links work without auth.

## 🐍 Python Version

v1.0 - GitHub Actions compatible (no Excel required)

# AutoFetchPortfolio

This repository acts as a dynamic control panel for my portfolio.

Instead of hardcoding which GitHub repositories to showcase, I maintain a curated list here in `featured.txt`. My portfolio site fetches this file at runtime and displays only the repos listed — giving me full control over what’s visible without needing to redeploy or modify frontend code.

## 🔧 How it works

- `featured.txt` contains one repo name per line.
- My site fetches this file from GitHub using the raw file URL.
- Only the listed repositories are displayed on the portfolio.

## ✅ Why this exists

I wanted a simple, GitHub-native way to manage my featured projects — especially as my repo list grows. This approach keeps my portfolio focused, flexible, and easy to update from anywhere.

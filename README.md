# Hi there! 👋

I'm $(jq -r '.name // .login' user_profile.json), a developer passionate about building things.

## 🔭 Recent Activity

$(if [ -s recent_repos.json ] && [ "$(jq length recent_repos.json)" -gt 0 ]; then
  echo "### Recent Repositories"
  jq -r '.[:5] | .[] | "- **" + .name + "**: " + (.description // "No description")' recent_repos.json
else
  echo "Working on various projects and contributions!"
fi)

## 📫 Get in touch

$(jq -r '.bio // "Always learning and building new things!"' user_profile.json)

---
*This README is automatically updated based on my GitHub activity*

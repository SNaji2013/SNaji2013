- 👋 Hi, I’m @SNaji2013
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
SNaji2013/SNaji2013 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
sudo mkdir -p /export/mirror/opencsw
sudo chown $LOGNAME /export/mirror/opencsw
rsync -aH --delete rsync://rsync.opencsw.org/opencsw/ /export/mirror/opencsw

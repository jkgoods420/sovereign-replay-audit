nano audit/audit.go
# Paste the Go code from previous message

nano audit/audit_test.go
# Paste the test code

nano src/verify_hmac.js
# Paste the JS code

nano scripts/bootstrap.sh
# Paste the bash script

nano scripts/sign_test_vector.sh
# Paste the bash script

nano .github/workflows/ci.yml
# Paste the YAMLchmod +x scripts/*.sh
./scripts/bootstrap.sh

git add .
git commit -m "Charter v2 - Shadow Monitoring - JMK"
git branch -M main
git remote add origin https://github.com/jkgoods420/sovereign-replay-audit.git
git push -u origin main

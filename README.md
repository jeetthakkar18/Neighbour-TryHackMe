# Neighbour-TryHackMe
TryHackMe Neighbour Lab
# Neighbour – TryHackMe IDOR Exploit

## 🛡 What is IDOR?
Insecure Direct Object Reference allows attackers to access unauthorized data by modifying references in the URL or parameters.

## 🧪 Challenge Summary
- Logged in as guest using hidden credentials.
- Modified user=guest to user=admin in URL.
- Gained access to admin zone and retrieved the flag.

## 🧰 Tools Used
- Browser DevTools (view source)
- Python requests (optional automation)

## 📈 Learnings
- Real-world IDOR vulnerability demonstration
- Understanding of broken access control
- Importance of validation and authorization in every endpoint

## 🏛 Room Info
- Platform: TryHackMe
- Room: Neighbour
- Difficulty: Beginner

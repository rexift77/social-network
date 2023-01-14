# Social Network
Social Network in SwiftUI with MVVM, 
Firebase for Login/Register and other database.


- Using Firebase 
  - Login with email
  - Register with email
- Firestore
  - Save all details of register user
  - Upload profile picture
- Post like
- Publish the post
- Fetch Profile detail
- Fetch all posts
- Fetch likes posts
- Fetch all register users
- Logout

To launch the mobile app, you will need:
1. Create a Firebase account (App).
2. Add the GoogleService-Info.plist file with your app data to the project (generated by Firebase).
3. Enable Authentication in Firebase (Sign-in providers): Email/Password.
4. Check and adjust the access rights of the Firestore Database (Cloud Firestore).

```
rules_version = '2';
service cloud.firestore {
  match /databases/{database}/documents {
    match /{document=**} {
      allow read, write: if request.auth != null;
    }
  }
}
```

# Screens
<img src="/Screens/screen-01.png" alt="screen-01" width="256" hspace="3"/><img src="/Screens/screen-02.png" alt="screen-02" width="256" hspace="3"/><img src="/Screens/screen-03.png" alt="screen-03" width="256" hspace="3"/><img src="/Screens/screen-04.png" alt="screen-04" width="256" hspace="3"/><img src="/Screens/screen-05.png" alt="screen-05" width="256" hspace="3"/><img src="/Screens/screen-07.png" alt="screen-07" width="256" hspace="3"/>

# 🏆 Awards
### Ranking #Dev: Global TOP 200 ([Certificate](https://leetcode.com/sergeyleschev/))

<a href="https://leetcode.com/sergeyleschev/"><img src="https://github.com/sergeyleschev/sergeyleschev/blob/main/leetcode-ranking.png" alt="drawing" width="410"/></a>

**Languages**: Swift, Shell, Database.

# 🚀 Developer Roadmap
- [X] S.Leschev iOS Developer [Roadmap](https://github.com/sergeyleschev/sergeyleschev/blob/main/sergeyleschev-ios-roadmap.md).

<div style="page-break-after: always;"></div>

## Contacts

I have a clear focus on time-to-market and don't prioritize technical debt. And I took part in the Pre-Sale/RFX activity as a System Architect, assessment efforts for Mobile (iOS-Swift, Android-Kotlin), Frontend (React-TypeScript) and Backend (NodeJS-.NET-PHP-Kafka-SQL-NoSQL). And I also formed the work of Pre-Sale as a CTO from Opportunity to Proposal via knowledge transfer to Successful Delivery.
 
🛩️ #startups #management #cto #swift #typescript #database

📧 Email: [sergey.leschev@gmail.com](mailto:sergey.leschev@gmail.com)

👋 LinkedIn: [https://linkedin.com/in/sergeyleschev](https://www.linkedin.com/in/sergeyleschev/)

👋 Twitter: [https://twitter.com/sergeyleschev](https://twitter.com/sergeyleschev)

👋 Github: [https://github.com/sergeyleschev](https://github.com/sergeyleschev)

🌎 Website: [https://sergeyleschev.github.io](https://sergeyleschev.github.io)

🌎 DEV Community: [https://dev.to/sergeyleschev](https://dev.to/sergeyleschev)

ALT: SIARHEI LIASHCHOU

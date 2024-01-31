`I'm still building this project, so I'll update this README as I go along.`

### use's settings
![image](https://github.com/Jonorusc/twitch-clone/assets/56327459/dd2ea37b-624f-45a4-8d69-1fdc7adaeaab)

### creator's settings
![image](https://github.com/Jonorusc/twitch-clone/assets/56327459/87bcccd7-8913-4b4d-bcf3-1d9a963938ac)
![image](https://github.com/Jonorusc/twitch-clone/assets/56327459/d8489777-cd58-4834-af09-b45b567cf068)



## Environment Variables Required

### .env

```bash
# PRISMA DATABASE
DATABASE_URL="mongodb+srv://USERNAME:PASSWORD@HOST/DATABASE"

# FIREBASE ADMIN SDK
# we use the public keys in order to access the firebase database on the client side
NEXT_PUBLIC_FIREBASE_API_KEY=""
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=""
NEXT_PUBLIC_FIREBASE_PROJECT_ID=""
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=""
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=""
NEXT_PUBLIC_FIREBASE_APP_ID=""
NEXT_PUBLIC_FIREBASE_MEASUREMENT_ID=""

# CUSTOM ENV VARIABLES
NEXT_PUBLIC_URL="http://localhost:3000"
```

# Preset Instructions

## SQLAlchemy URL
```
snowflake://preset@zppfzen-yk16582/AIRBNB?role=REPORTER&warehouse=COMPUTE_WH
```

## Security JSON
```json
{
    "auth_method": "keypair",
    "auth_params": {
        "privatekey_body": "-----BEGIN ENCRYPTED PRIVATE KEY-----\nMIIFNTBfBgkqhkiG9w0BBQ0wUjAxBgkqhkiG9w0BBQwwJAQQCUFfIm7eotFcBIV+\n07Jz4QICCAAwDAYIKoZIhvcNAgkFADAdBglghkgBZQMEASoEEKDmuZJkjJl4X7CD\nDkChcO8EggTQQMo9kTV4wxjkbEGGtERc6/p3DR4tJ0Vu/yRwExo7K4oEstYVFUcc\n8iNk+ucAjSs/SFNakE+NAYUq1SnCxtWe2wioZqeX1EybmCjRZwwh7P3qAmfKL+Q5\nhs/6WcLy0Xd6VvuaKmPfaPt8mLh8JpKuGQ5samDfatBEoY28ASbPlztmuJGjiAzq\nmrrFK3tSDu5e3dY44o0XuL2jV4z/47uO9EAFWNlsGo26jSW/sknv0WG628JkN4m9\nD47ik+rh1N/k8WwRIe2TGs/Ar4baaeJRp58y9cesjwn2gLaNH05n25h0U7C4jEHH\n1/Tg3C+6Ck7CcKPUG0oO0SmlVT2Yc4lGABSyitl3g/NTcIe45ThcWGX3b1iryc+4\nkpCrBNCE9fd+T5fz7VTvBrxgX06DSfIfdzp3Uzf4DMFKN33eZV9yx0rEtr1XtFSo\nqCtfXDn0THx4McQZZEwRSzaxee2YlJmH2GObIx4M7gwLGHqD36dT6tb1MQMC1U5U\nqco/T43f9wlCQBWPHcQnoGw8v0oAcV3gYtvDd5MBAVioOO0sIWyp2Pu5kHRELmqr\nP1o3enuExuJP2daI6/JuF4AYkmoCey3QxbBrCARQE+VgkG1bYp6PzqJqHheb6F0f\nP8T/j7BW3nS3t3op8GyYXFdcZHgt8xFffscnR3kYR0T9EiA8XCOJZiY//OIVzXiR\n29UTarLsJrXU+a0oVr5wWnc1g05MSJ2KxctKDC25jKF7d+f4uWjvp6uJwHTtvGUa\nxjhOgOUdbk8jSWieyWDEXBadY1cTpibXsnYly16H1ruO+d2mGcQfUC5AfxHZR2a5\noyTabtXHb6/cMStQcDG3kriTIsZ6dqPbmyng7tW6C16dMYFRT90wZqDICi0o5rSK\n4ID5Y3ONU/hxVZf8MHS7ozC5/qqVBJTMZIoYsEaVdV/V/5LzlDBCQnfAJLKcRdlo\ngw8dCHQQ6F2ZhT0dkpI7gKlWfs4MQpvSpeIRZelAYz1hnzagODcXXPq9nBAqnQdr\n0hguRRGmg2TY4nxOwEbRXdbpRY62iPi5fppNhf1XBLwzMcMDFtl2qWw2J06co4TI\nNa+I+XxwObhAweZBQbNQCxZq8eOs0mkcPknxkuwB+/BWM2pd4LzvhtH06kifIesY\n5jTDQtbBY7n83Qfgo4KimhBOXBLQQCrkVMbbJXqhZ5TMgq0nrHaFfDxZijcOSqMT\nMpptsG9UdhUXqNh6HSC4EBuZN2DOL5XnNcBXus4wFg14LTlg3NDThI/cFJ9uncsF\nAUWno2WVonv5G8D617HELFx0U/Z3qNr/0a5adLu5krmCRnTwmtamjYn0qe2iCegy\nyK3CL93spN9JsR9EDyTYL8h6bdnMLBPYDZehGkFVHR/GmH350eTSF2imzU04OZ88\nQMYtoG7IihaPPkm9UCXxjUThB+e+S9EYoIk2bw3vFux770SjtPUbg/6Psx5YBalP\nTNypPkfIwm8VRzvEglzjt8qGebXldkPy6isEdBwcTaI7o2vizzf2mIk5ot9gTRWm\nHiBJx8VEXrW1SO+010MJocREicezMNOvblvWEzus6qC5uQSMvSDhg6mkUBWpoicR\nGE+J7hDdteTrqE4LDe3U9SM2CS1otU72sR++YVxfzTy2ixOMSFneb5E=\n-----END ENCRYPTED PRIVATE KEY-----\n",
        "privatekey_pass": "q"
    }
}
```

## Instructions
1. Use the SQLAlchemy URL above to connect to your Snowflake database
2. Use the Security JSON configuration for authentication
3. The private key is already formatted with escaped newlines for direct use

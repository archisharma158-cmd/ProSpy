# ProSpy Research Document

## 1. Project Objective
Detect fake social media profiles using machine learning and profile behaviour analysis.

---

## 2. Selected Dataset

Dataset Name:
Fake Social Media Account Detection Dataset

Total Records:
3000

Platforms:
Instagram, Facebook, Twitter

Target Variable:
is_fake

---

## 3. Dataset Features

- has_profile_pic
- bio_length
- username_randomness
- followers
- following
- follower_following_ratio
- account_age_days
- posts
- posts_per_day
- caption_similarity_score
- content_similarity_score
- follow_unfollow_rate
- spam_comments_rate
- generic_comment_rate
- suspicious_links_in_bio
- verified

---

## 4. Selected Features for ProSpy

1. has_profile_pic
2. bio_length
3. username_randomness
4. followers
5. following
6. follower_following_ratio
7. account_age_days
8. posts
9. posts_per_day
10. spam_comments_rate
11. suspicious_links_in_bio
12. verified

Reason:
These features help distinguish fake and genuine accounts.

---

## 5. Fake Profile Indicators

1. No profile picture
2. Very short bio
3. Random username
4. Very low followers
5. Very high following
6. New account
7. Very few posts
8. Spam comments
9. Suspicious links in bio
10. Unusual follower/following ratio

(Add all 20 indicators)

---

## 6. Conclusion

The selected dataset contains relevant profile, content, and behaviour-based features suitable for training a fake account detection model.

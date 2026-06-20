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

| Feature                    | How it helps detect fake accounts |
|---------------------------|------------------------------------|
| has_profile_pic           | Fake accounts often use default or missing profile pictures, or stolen/random images. Real users are more likely to have personalized photos. |
| bio_length                | Very short or empty bios can indicate low-effort or bot accounts; overly spammy bios can also be suspicious. |
| username_randomness       | Random-looking usernames (e.g., many numbers/letters) often suggest auto-generated or bot-created accounts. |
| followers                 | Extremely low or extremely high followers (without context) can signal fake or bought accounts. |
| following                 | Bots often follow very large numbers of accounts to appear legitimate or to spam. |
| follower_following_ratio  | A very low ratio (many following, few followers) is common in spam/bot accounts; balanced ratios are more typical of real users. |
| account_age_days          | Newly created accounts are more likely to be fake or throwaway spam accounts. |
| posts                     | Very few posts can indicate inactivity or newly created fake accounts; extremely high posting may indicate automation. |
| posts_per_day             | Abnormally high posting rates often suggest automation or bot-like behavior. |
| spam_comments_rate        | High proportion of spam-like comments is a strong indicator of malicious or fake activity. |
| suspicious_links_in_bio   | Presence of phishing, affiliate spam, or shortened/masked links is a strong red flag for fake accounts. |
| verified                  | Lack of verification alone doesn’t mean fake, but verified accounts are significantly less likely to be impersonators or bots. |

Reason:
These features help distinguish fake and genuine accounts.

---

## 5. Fake Profile Indicators
| Indicator | Reason It May Suggest a Fake Profile |
|-----------|--------------------------------------|
| 1. Profile photo looks overly professional | Scammers and fake accounts often use stolen photos from models, influencers, or stock image websites. |
| 2. Only one or two photos available | Genuine users typically upload multiple photos over time showing different activities and settings. |
| 3. Recently created account | Fake accounts are often created shortly before being used for scams, spam, or impersonation. |
| 4. Very few friends or followers | A lack of social connections may indicate the account was not built through real interactions. |
| 5. Unusual follower-to-following ratio | Following thousands of accounts while having very few followers can be a sign of artificial account growth. |
| 6. Incomplete profile information | Fake profiles frequently leave personal details blank to avoid verification and scrutiny. |
| 7. Inconsistent personal details | Differences in age, location, occupation, or education across the profile may indicate deception. |
| 8. No tagged photos from other people | Genuine users often appear in photos posted or tagged by friends, family, or colleagues. |
| 9. Generic or copied bio | Scammers commonly reuse the same biography text across multiple fake accounts. |
| 10. All posts uploaded within a short period | Fake profiles may be populated quickly to appear legitimate without a natural posting history. |
| 11. Repetitive or generic comments | Automated bots often leave similar comments that lack context or personalization. |
| 12. Refuses video calls or live verification | Avoiding real-time interaction can help conceal a false identity. |
| 13. Quickly requests communication off-platform | Moving to private messaging apps can bypass platform safety and monitoring systems. |
| 14. Requests money or financial assistance | Financial requests are a common objective of romance scams and fraudulent profiles. |
| 15. Claims a prestigious profession without evidence | Fake profiles often use attractive or high-status occupations to gain trust quickly. |
| 16. Location does not match activity | Posts, timestamps, language, or check-ins may conflict with the claimed location. |
| 17. Photos appear inconsistent with claimed identity | Differences in age, ethnicity, lifestyle, or appearance may indicate stolen images. |
| 18. Writing style changes significantly | Multiple operators or AI-generated messages can cause noticeable changes in communication style. |
| 19. Avoids answering basic personal questions | Fake account operators may struggle to maintain a consistent fabricated identity. |
| 20. Reverse image search finds matches elsewhere | Discovering the same image linked to another person strongly suggests identity misuse or impersonation. |

## Risk Assessment

| Number of Indicators Present | Risk Assessment |
|-----------------------------|-----------------|
| 0–4 | Low likelihood of being fake |
| 5–9 | Moderate likelihood; further verification recommended |
| 10–14 | High likelihood; exercise caution |
| 15–20 | Very high likelihood; profile may be fraudulent or impersonating someone |

---

## 6. Conclusion

The selected dataset contains relevant profile, content, and behaviour-based features suitable for training a fake account detection model.

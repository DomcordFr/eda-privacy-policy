# Eda Bot - Privacy Policy

**Effective Date:** September 1, 2026

This Privacy Policy explains how Eda ("the Bot"), a Discord moderation and server management bot, collects, uses, stores, and protects your data. Eda is self-hosted and operated by Dominion ("the Operator"). 

By using Eda or interacting in a Discord server where Eda is active, you agree to the practices described in this policy.

---

## 1. What Data We Collect and Why

We collect only the specific data necessary to provide effective moderation, security, and management features to server administrators. We do not collect data for tracking or advertising purposes.

*   **Discord Account Information:** We collect User IDs, usernames, display names, and role IDs. 
    *   *Why:* To verify staff permissions, apply moderation actions, and manage "sticky roles" (automatically restoring a user's roles if they leave and rejoin the server).
*   **Message Content (Strictly Limited):** We **do not** perform bulk logging or monitor normal conversations. Message content is only collected and stored when a message triggers a security or moderation protocol:
    *   *AutoMod:* Messages that trigger spam, phishing, or word blacklist filters.
    *   *Honeypots:* Messages sent by malicious actors or bots in designated, hidden honeypot channels.
    *   *Audit Trails:* The text of edited or deleted messages is temporarily cached to provide staff with a reliable moderation audit trail.
*   **Moderation Case Data:** We log warnings, mutes, kicks, and bans, along with the reason, timestamp, and the Discord ID of the staff member who issued the action.
    *   *Why:* To provide server administrators with an accurate historical record of rule enforcement.

## 2. Legal Basis for Collection

We collect and process this data under the legal basis of **legitimate interest**. Our legitimate interest is to provide robust security, moderation, and community management services to the Discord server administrators who elect to install Eda.

## 3. Data Retention

We keep data only as long as necessary to fulfill the purposes outlined above:

*   **Moderation Case Logs & Sticky Roles:** Retained indefinitely by default to ensure an accurate historical audit trail and prevent users from bypassing punishments by leaving and rejoining.
*   **Message Content Logs (Edited/Deleted Messages):** Retained temporarily for the staff audit trail and purged automatically after **30 days**.

## 4. Requesting Data Deletion

Users have the right to request the deletion of their stored data. 

To request deletion, you may contact the administrators of the server where the action occurred, or email the Operator directly at **support@domcord.org**. We will process verified deletion requests within **30 days**. 

*Note: We reserve the right to retain certain moderation records (such as active bans or severe security threat logs) if necessary to protect the safety and integrity of the server.*

## 5. What Happens When the Bot is Removed

If Eda is removed (kicked) from a Discord server, all server-specific configuration data, audit logs, and member tracking histories associated with that server will be permanently deleted from our database within **30 days**, except where the server administrator explicitly requests temporary retention for legal or severe security reasons.

## 6. Security Measures

Your data is secure. Eda is self-hosted on the Operator's own private server infrastructure. All data is stored locally in an isolated SQLite database. 
*   We **do not** use third-party cloud database providers. 
*   We **do not** use third-party data processors.
*   Access to the server and database is strictly restricted to authorized operators.

## 7. Children's Privacy

Eda operates exclusively on the Discord platform, which requires users to be at least 13 years old. Eda is not directed at children under 13, and we do not knowingly collect personal information from anyone under 13.

## 8. Third-Party Sharing and AI Training

*   **No Third-Party Sharing:** We do not sell, rent, or share any collected data with third parties. All processing occurs strictly "on-platform" (between Discord's API and our local database).
*   **No AI Training:** Absolutely no message content or user data is used to train Artificial Intelligence or Machine Learning models.

## 9. Changes to this Policy

We may update this Privacy Policy from time to time. Updates will be communicated via official announcements in our primary support server or through direct updates to this hosted document. Continued use of Eda after changes are published constitutes your acceptance of the revised policy.

## 10. Contact Information

For privacy inquiries, questions about this policy, or to submit a data deletion request, please contact us at:
**Email:** support@domcord.org

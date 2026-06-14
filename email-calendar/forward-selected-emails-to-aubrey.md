# Forward selected emails to Aubrey

You can forward emails to Aubrey so your agent can store messages, summarize them, or use them as context.

Most people should forward selected emails with rules or filters instead of forwarding every message in their inbox.

Use full-inbox forwarding only when you are comfortable sending all new mail from that account to Aubrey.

## Before you start

Open your agent in Aubrey and copy the agent email address shown in the **Email** section. It will look similar to:

```
alexjohnson@agent.helloaubrey.com
```

Aubrey handles email in three ways:

* Forward an email to Aubrey to store it.
* Email Aubrey directly when you want a reply.
* Cc Aubrey with an explicit request when you want Aubrey to collaborate in a thread.

For forwarding setup, use the Aubrey email address as the destination.

## Recommended: forward only selected emails

Rule-based forwarding keeps your personal inbox private and sends only matching emails to Aubrey.

Good rule examples include:

* Emails from a specific sender, such as a newsletter, vendor, client, or family member.
* Emails with a subject that contains a project name.
* Emails sent to a specific alias.
* Receipts, invoices, confirmations, or reports you want Aubrey to remember.

Gmail and Outlook support rule-based forwarding. Yahoo automatic forwarding is an account-level setting, and Yahoo filters organize messages into folders or trash rather than forwarding matching messages to another address.

## Gmail: forward selected emails with a filter

Gmail lets you forward all new messages or only messages that match a filter. Google recommends turning off automatic forwarding and using a filter when you only want certain messages forwarded.

### Step 1: Add your Aubrey address as a forwarding address

1. Open Gmail on a computer.
2. Sign in to the Gmail account you want to forward from.
3. Click the gear icon.
4. Click **See all settings**.
5. Open **Forwarding and POP/IMAP** or **Forwarding**.
6. In the Forwarding section, click **Add a forwarding address**.
7. Paste your Aubrey email address.
8. Click **Next**, then **Proceed**, then **OK**.

Gmail sends a verification message to the forwarding address before the address can be used.

### Step 2: Confirm the Gmail verification in Aubrey

1. Return to Aubrey and open your agent page.
2. Look for the Gmail forwarding setup prompt.
3. Open the Gmail confirmation link from Aubrey.
4. After confirming, return to Gmail settings and refresh the page.

### Step 3: Create the Gmail filter

1. In Gmail, click the search options icon in the search bar.
2. Enter the rule criteria, such as:
   * From: a sender email address.
   * To: a specific alias.
   * Subject: a keyword or project name.
   * Has the words: a phrase you want to match.
3. Click **Search** first if you want to test the criteria.
4. Click **Create filter**.
5. Select **Forward it**.
6. Choose your Aubrey email address.
7. Click **Create filter**.

Do not turn on **Forward a copy of incoming mail to** unless you want Gmail to forward all new non-spam messages.

## Outlook.com or Outlook on the web: forward selected emails with a rule

Use Outlook rules when you want Aubrey to receive only matching messages. For Aubrey, choose **Forward to** unless support specifically tells you to use redirect.

Forwarded messages appear as forwarded from your account. Redirected messages appear to come from the original sender.

1. Open Outlook.com or Outlook on the web.
2. Click **Settings**.
3. Go to **Mail** -> **Rules**.
4. Click **Add new rule**.
5. Give the rule a clear name, such as `Forward invoices to Aubrey` or `Forward project updates`.
6. Under **Add a condition**, choose the messages you want to send to Aubrey. For example:
   * From a specific sender.
   * Subject includes a keyword.
   * To or Cc includes a specific alias.
7. Under **Add an action**, choose **Forward to**.
8. Paste your Aubrey email address.
9. Add exceptions if needed.
10. Leave **Stop processing more rules** selected if this rule should prevent later rules from also applying.
11. Click **Save**.

If Outlook shows **Sign in and verify your account to create a forwarding rule**, click **Sign in** and complete Microsoft's verification.

## Yahoo Mail: forwarding options

Yahoo automatic forwarding requires Yahoo Mail Plus and may not be available in every locale. Yahoo sends verification instructions to the forwarding address after you click **Verify**.

Yahoo filters can sort new emails into a folder or trash. Yahoo's filter help does not describe forwarding matching filter results to another email address.

### Option A: use Yahoo automatic forwarding

Use this only if you want Yahoo to forward incoming mail from that mailbox to Aubrey.

1. Open Yahoo Mail.
2. Click **Settings**.
3. Click **More Settings**.
4. Click **Mailboxes**.
5. Select your primary mailbox.
6. Under **Forwarding**, enter your Aubrey email address.
7. Click **Verify**.
8. Yahoo sends verification instructions to the forwarding address.

Because the forwarding address is an Aubrey address, the Yahoo verification email is delivered to Aubrey. If you do not see a Yahoo verification prompt in Aubrey, contact support and include the Yahoo address you are setting up and the Aubrey address you used.

### Option B: use Yahoo filters without forwarding

If you do not want to forward every Yahoo email, use Yahoo filters to organize matching messages into a folder, then manually forward only the messages you want Aubrey to store.

1. Open Yahoo Mail.
2. Click **Settings**.
3. Click **More Settings**.
4. Click **Filters**.
5. Click **Add new filters**.
6. Enter a filter name.
7. Set the filter rules.
8. Choose or create a folder for the matching emails.
9. Click **Save**.

Yahoo filters are prioritized from top to bottom.

## Optional: forward all email

Only use full forwarding when you want all new mail from the provider account sent to Aubrey.

### Gmail: forward all new mail

1. Open Gmail on a computer.
2. Click the gear icon.
3. Click **See all settings**.
4. Open **Forwarding and POP/IMAP** or **Forwarding**.
5. Click **Add a forwarding address**.
6. Add your Aubrey email address.
7. Confirm the Gmail verification in Aubrey.
8. Return to Gmail settings and refresh the page.
9. Select **Forward a copy of incoming mail to**.
10. Choose your Aubrey email address.
11. Choose what Gmail should do with its own copy. Google recommends keeping Gmail's copy in the Inbox.
12. Click **Save Changes**.

### Outlook.com: forward all new mail

1. Open Outlook.com.
2. Click **Settings**.
3. Go to **Mail** -> **Forwarding**.
4. Select **Enable forwarding**.
5. Enter your Aubrey email address.
6. Optional: select **Keep a copy of forwarded messages**.
7. Click **Save**.

Microsoft may ask you to enable two-step verification or verify your identity when enabling forwarding.

### Yahoo Mail: forward all new mail

1. Open Yahoo Mail.
2. Click **Settings**.
3. Click **More Settings**.
4. Click **Mailboxes**.
5. Select the primary mailbox.
6. Under **Forwarding**, enter your Aubrey email address.
7. Click **Verify**.
8. Follow the verification instructions sent to the forwarding address.

Yahoo says this feature requires Yahoo Mail Plus and may not be available in all locales.

## Test your setup

After creating a forwarding rule or turning on full forwarding:

1. Send a test email that matches the rule.
2. Wait a minute.
3. Open Aubrey.
4. Check the agent that owns the Aubrey email address.

If the message does not appear, confirm that:

* The forwarding destination exactly matches the Aubrey address.
* The rule criteria match the test email.
* The rule is saved and enabled.
* The provider verification step is complete.
* The email was not sent to spam before forwarding.

## Troubleshooting

### Gmail added the address, but emails are not forwarding

Adding the forwarding address is only the first step. After confirming the Gmail verification link in Aubrey, return to Gmail and create a filter with **Forward it**, or enable **Forward a copy of incoming mail to** if you want full forwarding.

### Gmail is forwarding too much

Turn off automatic forwarding and use a Gmail filter instead. Automatic forwarding sends all Gmail messages by default, while filters let you forward only messages that match specific criteria.

### Outlook asks me to sign in or verify my account

Complete Microsoft's verification step, then return to **Mail** -> **Rules** or **Mail** -> **Forwarding** and save the rule or forwarding setting.

### Outlook has both "Forward to" and "Redirect to"

Choose **Forward to** for Aubrey. Forwarded messages appear as forwarded from your account, while redirected messages appear to come from the original sender.

### Yahoo does not show forwarding

Yahoo says forwarding requires Yahoo Mail Plus and is not available in all locales. If the option is not listed in your account, Yahoo says it is not available at this time.

### Yahoo verification does not appear in Aubrey

Yahoo sends verification instructions to the forwarding address. Since the forwarding address is an Aubrey address, contact support if the verification email does not appear in Aubrey after you click **Verify**.

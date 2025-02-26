# Configure default settings for new users

{!admin-only.md!}

Organization administrators can configure the default values of
personal preference settings for new users joining the
organization. This can help seamlessly customize the Zulip experience
to match how the organization in question is using Zulip.

Existing users' preferences cannot be modified by administrators, and
users will be able to customize their own settings once they
join. Administrators can customize defaults for all personal
preference settings, including the following:

* Privacy settings:
    * [Displaying availability to other users](/help/status-and-availability)
    * [Allowing others to see when the user has read messages](/help/read-receipts)

* Preferences:
    * [Language](/help/change-your-language)
    * [Time format](/help/change-the-time-format)
    * [Light theme vs. dark theme](/help/dark-theme)
    * [Emoji theme](/help/emoji-and-emoticons#change-your-emoji-set)
    * [Default view](/help/configure-default-view)
      ([Inbox](/help/inbox) vs.
      [Recent conversations](/help/recent-conversations) vs.
      [All messages](/help/reading-strategies#all-messages))

* Notification settings:
    * [What types of messages trigger notifications][default-notifications]
    * [Configurations for email notifications](/help/email-notifications)

[default-notifications]: /help/stream-notifications#configure-default-notifications-for-all-streams

## Configure default settings for new users

{start_tabs}

{settings_tab|default-user-settings}

1. Review all settings and adjust as needed.

{end_tabs}

## Configure default language for new users

Your organization's [language](/help/configure-organization-language) will be
the default language for new users when Zulip cannot detect their language
preferences from their browser, including all users [created via the Zulip
API](/api/create-user).

{start_tabs}

{settings_tab|organization-settings}

1. Under **Automated messages and emails**, change the **Language for
   automated messages and invitation emails**.

{!save-changes.md!}

{end_tabs}

## Related articles

* [Setting up your organization](/help/getting-your-organization-started-with-zulip)
* [Customize settings for new users](/help/customize-settings-for-new-users)
* [Set default streams for new users](/help/set-default-streams-for-new-users)
* [Invite users to join](/help/invite-users-to-join)

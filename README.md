# Application information, privacy policy and terms of use

*Last updated: 2026-11-06*

This page is the home page, the privacy policy and the terms of use of a private application ("the application") that
its developer, who is also its only operator ("the operator"), runs on computers he controls. It is not offered to the
public: there is nothing to sign up for, there are no other users, and nobody except the operator signs in to it.

## What the application is

A personal automation tool. It prepares video files and publishes them to a YouTube channel that the operator owns,
through the YouTube Data API. It signs in only to the operator's own Google account.

## Google user data

**What it accesses, and why.** After the operator signs in once and agrees, the application holds a Google OAuth token
for the operator's own account with these permissions (scopes), and uses them only for the purposes given:

- `https://www.googleapis.com/auth/youtube.upload`: to upload videos and thumbnails to the operator's channel.
- `https://www.googleapis.com/auth/youtube`: to update the title, description, tags and settings of videos the
  application itself uploaded, and to check that they were processed.

It does not read, collect or process any other person's Google data.

**Storage.** The token is stored in a private file that only the operator's user account can read, on computers the
operator controls. The videos and related files stay on those computers too. No server run by anyone else receives them.

**Sharing.** The application does not sell, rent, transfer or disclose Google user data to anyone. It does not use it for
advertising or profiling, it does not train AI or machine-learning models on it, and nobody reads it except the operator.

**Limited Use.** The application's use and transfer to any other app of information received from Google APIs adheres to
the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including
the Limited Use requirements.

**Retention and deletion.** The token is kept for as long as the operator wants the application to work. It is deleted
when the operator removes it from the computers, and it stops working at once when access is revoked at
[myaccount.google.com/permissions](https://myaccount.google.com/permissions).

## YouTube API Services

The application uses YouTube API Services. By using them through this application you agree to be bound by the
[YouTube Terms of Service](https://www.youtube.com/t/terms). How Google handles data is described in the
[Google Privacy Policy](https://policies.google.com/privacy).

## Privacy policy

This page collects no information about the people who read it: no cookies, no analytics, no forms. The only personal
data the application handles is the Google OAuth token described above, which belongs to the operator. The application is
not directed at children. Security rests on the token file's permissions and on the operator's control of the computers
it runs on. If this policy changes, the date at the top changes with it.

## Terms of use

The application is for the operator's personal use and is provided "as is", without warranties of any kind. The operator
is not liable for any loss arising from it. The operator may change or stop the application at any time. Nothing on this
page grants anyone a right to use it.

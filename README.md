# Minimal Terms of Use and Privacy Policy

## Why?

When creating an open source application,
[choosing a license](https://choosealicense.com/) for the source code is easy.

However, when hosting the same application to make it available for everyone
online, **writing Terms of Use and a Privacy Policy is much more difficult**.

Plenty of templates and generators are available, but they often create long
documents in which most of the content doesn't remotely apply to a simple,
non-commercial work.

Therefore, many developers don't bother placing any legal text on their app.

**It would be great to have something as simple as the MIT license, for Terms of
Use and Privacy Policy.** This is what this project attempts to do.

The main goals are:

- limitation of liability
  - for instance, to prevent the app owner from being liable if a bug in the app
    incurs a loss to a user;
- declaration of information that may be collected
  - which might be required in some jurisdictions.

> [!WARNING]
>
> I am not a lawyer. Nothing in this project can be interpreted as legal advice.
> This project is in its infancy, and is licensed with the MIT license. I
> provide it in the hope that it can be useful, and that people knowledgeable in
> the area will contribute, but it comes without any warranties.

> [!TIP]
>
> Are you a lawyer? Please provide your feedback and contribute!

## Who is this for, and how to use it?

This is primarily intended for individual developers making an app which:

- is a personal project,
- is open source,
- is completely free,
- doesn't have any kind of login system (users can't create accounts),
- doesn't collect personal user data,
- doesn't use cookies.

> [!NOTE]
>
> The app can have simple analytics and error reporting tools. You need to make
> sure that these tools don't use cookies and don't send personal user data.

Simply place the following Terms of Use and Privacy Policy on your app, and
replace all elements like `**<your-name>**` with the corresponding information.
You might replace `Application` by `Website` (keep the first letter capitalised
where it is as such). Also note that some parts are optional, and decide if you
want to include any of them.

```md
# Terms of use

These Terms of Use ("Terms") govern your use of this application hosted and
provided by **<your-name>** ("we", "us", or "our"), ("Application") and any
services offered through the Application ("Services").

We may change these Terms or modify any features of the Application or the
Services at any time. Any such change or modification will be effective
immediately upon posting on our Application. You accept these Terms by using the
Application and/or the Services, and you accept any changes to the Terms by
continuing to use the Application and/or the Services after we post any such
changes.

If you do not agree to these Terms, please do not access or use the Application.

## Limits on liability

The Application and Services are provided "as is", without warranty of any kind,
express or implied, including but not limited to the warranties of
merchantability, fitness for a particular purpose and noninfringement. We make
no guarantees that they always will be safe, secure, or error-free, that they
will function without disruptions, delays, or imperfections or content will be
accurate, current and complete.

## [Optional part: include if users can submit content] Content standards

You must not submit content that is illegal.

Takedown requests can be sent to **<your-contact-information>**.

## Links to third-party content

The Application or Services may contain links to third-party content, over which
we have no control and for which we have no responsibility.
```

```md
# Privacy policy

This Privacy Policy describes **<your-name>** ("we", "us", or "our") practices
for handling your information in connection with this application
("Application") and any services offered through the Application ("Services").
This Privacy Policy describes the personal information we process to support our
Services.

We may change this Privacy Policy at any time. Any such change will be effective
immediately upon posting on our Application. You accept this Privacy Policy by
using the Application and/or the Services, and you accept any changes to the
Privacy Policy by continuing to use the Application and/or the Services after we
post any such changes.

If you do not agree to these Privacy Policy, please do not access or use the
Application.

## What kinds of information is collected?

Depending on the type of device you use and how you interact with us, we may
collect certain information automatically when you use our Services, such as:

- Device attributes, including information such as the operating system,
  hardware and software versions, browser type.
- Network and connections information, such as your IP address.
- Browsing information, such as the referrer URL identifying the address of the
  web page which linked you to our Application.
- Application performance information, such as software errors if they occur.

Our Application and Services are hosted by hosting providers, such as Amazon,
Google, Microsoft. These hosting providers may also collect the information
described above.

## How do we use this information?

We use the information described above for:

- analytics purposes, such as knowing the number of users, and which features
  are the most popular;
- performance and error reporting purposes, such as being alerted if an error
  occurs in our Application.
```

## Contributing

I you're a lawyer, and/or have knowledge in this area, and/or have resources
which could be useful to this project. Please contribute by simply
[creating an issue in this project](https://github.com/Zwyx/minimal-terms-of-use-and-privacy-policy/issues/new).

Please keep in mind: the purpose of this project is to stay as simple as
possible.

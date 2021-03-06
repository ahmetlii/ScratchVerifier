# ScratchVerifier Information
## What this is and is not
This is not:
- a platform for Scratchers to use except as an API for programs
- a website that allows you to link accounts, or a social media

This is
- an API for Scratch account verification

## Guidelines
Please read our [Code of Conduct](https://github.com/ScratchVerifier/ScratchVerifier/blob/develop/CODE_OF_CONDUCT.md) before proceeding. 
The following behaviour is discouraged:
- Posting issues with very simple descriptions, or unconstructive criticism. We would like you to explain in detail what can be done, what is wrong and what could get an update.
- Irrelevant discussions: Please move to our Discord [(invite)](https://discord.gg/qQxn5qUhSA) to continue any discussions. Any long off-topic discussions could make the discussion get marked as offtopic, removed or the issue locked outright if the problem is worse enough.
- PRs with nearly no effort: We want to make quality code, so please submit a PR that has work in it. Copying code is fine, (everyone does that) but we will not accept any changes which do not provide any benefit to the project or its users. Also, please explain what your PR includes so we can review it and prevent confusions.
- PRs which require modules or code from a private project: We are trying to make this a self-hostable application. Any PR making this project non-self hostable will be rejected. Also, we are self hosting and checks require the service to be able to be started with a clean slate, if possible with nearly no effort.

The following behaviour is prohibited:
- Spam and advertisements: Please do not advertise in our repository. You may link to other sites for the sole purpose of providing context to issues, or our Discord only to continue a discussion.

Recommendations:
- You might want to check the issue templates so we can understand your issue easier and fix it or add it.
- Please consider how your PR may affect how self hosting works. Any major changes might be rejected.
- Please include tests for your PR if it is a feature proposal; otherwise, we don't necessarily require tests. Note that there are some exceptions where we don't require tests; we will tell you if that is the case.
- Please keep the original style in the code, such as how tests work, authentication works or the database schema. If a database schema change is required, try to ensure that the changes only involve creating new tables if the feature is entirely new, or include plans to migrate the data, which can be expressed in SQL form.
- If your PR addresses an issue or issues, please link it.
 
## Who to assign/tag for an issue:
|Type            |User                 |
|----------------|---------------------|
|Design/Frontend |Semisol, Accio1      |
|Backend         |Kenny2github, Semisol|
|Docs            |Kenny2github         |

Our Discord for support is also available at: [here](https://discord.gg/qQxn5qUhSA)

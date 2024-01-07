<h1>Identity and Access Management (IAM)</h1>
<h2>Introduction</h2>
Is a Global Service (have 1 global DB for your account) and Global Resilience  (any data is always secured across all AWS Regions).

- It has no Cost.
- Your IAM instance is separated form any other AWS Accounts.
- Your AWS Account FULL TRUST your IAM and will trust the same way any identity the IAM creates.
- IAM (like root user) can do <i>anything</i> in your account.

>[!NOTE]
> Least Privilage Access: give only the permissions required to do a job or perform a task.

<h2>Identities</h2>
It can create 3 different types of identity obejcts:

- User: represent humans/applications that need access to your AWS account
- Group: colelction of related users.
- Role: can be used by AWS Services, or for granting external access to your account.
- "Policy": objects or documents used to Allow/Deny access to AWS Services when they are attached to users/groups/roles (by themselves do nothing).
>[!IMPORTANT]
> Users are used when you can identify the individual thing (person/app) that will logging to that user.
>
> Roles are used when the number of things is uncertain (eg users form external accounts, x number of EC2 instances for AWS services themselves...)

<h2>Jobs</h2>
It has 3 main jobs:

- IDP (ID Provider): create/modify/delete identities (users/groups/roles)
- Authenticate: those identities (prove you are who you claim to be)
- Authorize: (once you are authenticated) allow/deny access to resources (IAM policy)

It has no direct control on external accounts or users

<h2>Access Keys</h2>
Long-Term Credentials (don't change automatically/regularly)

- 1 IAM User can have 0-1-2 access keys (idependent fo their state).
- The only Identities which use Access Keys are IAM Users.
- Can be create/delete and made inactive/active (default).
- Can't be edited (can't change secret key without changing access key)

Have 2 parts ->  Access Key ID & Secret Access Key (more complex, only visible 1 time (never more))


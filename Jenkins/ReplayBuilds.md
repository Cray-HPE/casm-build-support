# How to replay a build

If your user account (which is setup via github auth into jenkins) has `admin` rights to a repo, then you will have 'replay' authority to a build in Jenkins; otherwise you will only have 'rebuild' authority.

Replaying a build can be very helpful because it allows you to rapidly 'inject' into your jenkinsfile wtihout having to make code changes.  Note: These changes do not persist, and this can be a privelege escalation vector so do not give people who do not need explicit access to this ability permissions if not needed. 
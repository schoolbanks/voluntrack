# voluntrack

High school students all over America are required to complete volunteer hours for graduation.
That's an awesome thing. Teaching kids the valuable lesson of giving back.

The problem is that nearly all of the school districts use pen and paper to track these activities.

My proposal is to create web based platform than any school district can use to accurately record, track, validate, and report on student volunteer hours.

A school member would sign up using their district email.
Once their email is validated, their email domain is used to link other users from the same district to the same instance.
Students are invited by sending a unique site up link to their students and restricting the email domain their students can use to sign up.

Once the account is created, students will complete a volunteer activity, then record it in the web app using the simple intake form.
The form will require contact information of person over the volunteer activity.
The person over the activity will receive an email where they need to click a link to validate the volunteer hours entered by the student.
Once validated, the hours will be counted.

If the volunteer agency is new to the system, the details will be sent to a school administrator on the students behalf to verify the volunteer agency.
Once the agency is verified, a verified seal will also show alongside the students hours indicating that the volunteer hours were an approved agency.
If the agency was not verified, the hours would not be counted and the studwnt would receive an email alerting them that the hours were no longer counted with the reason the agency was not verified.
Unverified agencies would not be able to verify a students activities until they are re-evaluated by the initial school that unverified them or they are verified directly by the web app administration team.

Both students and school administration should be able to enter volunteer hours for a student. However when entered by an administrator, the agency is auto verified.

Known agencies are linked by their private email domain. If they use a public email domain, they are only linked by the full email address.

School systems will be able to use this app at no cost for their first 50 students. Once they reach student 51, they will have to pay $1 per student per year to use the platform.
There are 15.1 million high school students in the US in 2022.

This solution will need to:
- align with the OneRoster 1.2 standard - https://www.imsglobal.org/sites/default/files/spec/oneroster/v1p2/rostering-informationmodel/OneRosterv1p2RosteringService_InfoModelv1p0.html
- allow quick sign up and login with Microsoft/Office 365 and Google Classroom/Workspace accounts.

# SIMPLE IRA Plan Details

## Caveat

Nothing in this document is tax, legal, or financial advice, sorry.


## Version history

### Future versions

 - None planned

### Current version
 - v1.1.0, 2023-11-29: Updates and tweaks

### Previous versions
 - v1.0.1, 2023-07-06: Tweaks to admin documentation
 - v1.0.0, 2021-04-23: Launch of IRA plan availability


## Overview

In general, retirement plans allow employers to send some of your compensation directly to a retirement account you create before you pay taxes on it, instead of depositing it in your normal personal account. This means that money that would normally go towards taxes can instead sit in a retirement account making money. If you have a retirement account available to you, it is usually a very good idea to take advantage of it. Generally speaking, you will have more money when you retire.

For example, imagine that you get $1000 on a given paycheck, but that the government taxes you at a 30% rate. Without a retirement account, you'll be paid $1000 × 30% = $700 each pay period, which you'll invest. If, instead you use a retirement account, you'll get the whole $1,000 to invest for the next few decades and you'll pay taxes on it later, when you retire and take the money out of the account. By using the retirement account, you have 30% more money to invest.

Many for-profit organizations have 401(k) plans for this purpose. Non-profits like ours can have something similar called a 403(b) plan, but both of those plan types require that employers pay big fees to the bank that provides the service. They are also very difficult to administer (see FAQs below) — They're for bigger companies than ours. For organizations like ours, there's something called a [SIMPLE IRA Plan][simple], that is actually quite simple and works similarly, with the main downside being that it has a lower per-year maximum contribution rate.

 
## Eligibility

All full time employees are eligible to receive this benefit and are encouraged to take advantage of it.


## Benefit

Eligible employees may make salary reduction contributions to the plan.

Free Law Project will match your contributions up to the legal limit of 3% of your compensation.

Contributions may be changed on no more than a monthly basis.

The [maximums that invividuals can contribute][irs-cr] vary year to year. The following apply unless over age 50 (in which case other details apply):

 - 2024: $16,000/year
 - 2023: $15,500/year
 - 2022: $14,000/year
 - 2021: $13,500/year
 - 2020: $13,500/year
 - 2019: $13,000/year

At Free Law Project, we are paid every other week, creating 26 payments/year. Therefore your maximum deferral is the annual limit divided by 26. For example, in 2024, that amount is $16,000/26 = ~$615.


## Getting Started as an Employee

The first thing you have to do is create an account with our plan provider, American Century Investments.

To do that:

1. Complete [the form here][setup]. It will ask you a couple tricky questions. Here are the answers:

     - Yes, FLP has designed American Century Investment as the Designated Financial Institution.
       
     - Our plan ID is: 153337001
    
2. After you have completed the form above, you'll have to wait two days for them to get things set up. Then, you can create an online [here][register]. Don't forget to set up 2FA!

[setup]: https://www.americancentury.com/content/direct/en/insights/workplace-retirement/plan-participants/simple-ira.html#enroll
[register]: https://www.americancentury.com/sd/registration/start

3. Once you have your online account set up, you'll need to start your contributions (you can later use this same approach to adjust them). To do so, copy/paste the snippet below and send it to mike@free.law:

> Subject to the requirements of the SIMPLE IRA plan of Free Law Project, I authorize $_________ to be withheld from my pay for each pay period and contributed to my SIMPLE IRA account as a reduction contribution.
>
> I understand that the total amount of my salary reduction contributions in any calendar year cannot exceed the applicable amount for that year.
>
> I understand that my salary reductions will start as soon as permitted under the SIMPLE IRA plan and as soon as administratively feasible.
>
> This salary reduction agreement replaces and earlier agreement and will remain in effect as long as I remain an eligible employee under the SIMPLE IRA plan or until I provide Free Law Project with a request to end my salary reduction contributions or provide a new salary reduction agreement as permitted under this SIMPLE IRA plan.
>
> Signed: ______________________________
>
>
> Date: ________________________________

Once we receive the above notification from you, we will ask the bank to reflect your contributions at the next pay period or as soon as possible.


## Q&A

Q: How do I set up my personal account?

A: Go here and create an account: https://www.americancentury.com/ms/adpparticipant/ui

Q: How do I invest my contributions?

A: Simply log into your account with American Century Investments, and you can make your allocations via their website. If you need help, you can call them. They currently have a small fee per fund that you invest in, but check their fee schedule for details.

Q: I prefer bank XYZ. Can we use them?

A: Probably not. In setting this up, we researched the following:

 - *Schwab* doesn't do auto-investment, so you have to re-invest your contribution after every pay period or else it sits in your cash account where it will probably lose money due to inflation.

 - *Fidelity & Vanguard* have administrative processes that require that somebody do busy work before every pay period. If no employee changes their contributions during the pay period, you literally have to upload the same info to their website every pay period over and over, forever.

 - *Nationwide, Union Bank & Lincoln Financial* don't do SIMPLE IRAs.

 - *ADP* charges about $500 in fees each year.

Anyway, point being that we're open to considering it, maybe, but most of the banks don't fit us or have bad offerings.

Q: Why not do a 403(b) plan?

A: Because they're complicated and expensive. For example, Vanguard offers such a plan, but it would cost FLP $750/year + $90/employee. On top of that, it takes 6-8 weeks to set up, FLP has to select the available funds and make a "plan document." Even once all that is done and paid for, you have to do busy work every pay period just like their SIMPLE IRA plan. Fidelity won't even talk to you about a 403(b) plan until you've got $75M in assets.

Q: Something else?

A: Email mike@free.law


## For the Plan Administrator

On the employer side, you can tweak things via the administrator account. You can [log into it here][admin].

[admin]: https://www.americancentury.com/info/psa/

### Adding a new contribution

This has to be done in two places. First, go to the link above, then Payroll --> Add New Payroll --> Systematic. That'll take you to a wizard. In the first step of the wizard, unckeck the boxes under "Compliance testing" and under "Additional items." Do check "Employee Deferral" and "Employer Match". When you submit that form, it'll show all employees (yes, this really should show everybody that's set up), and you can tweak their deferments. 

You will have to re-enter the deferments for all previous employees (See below for calculating this). Payroll is every-other week on Fridays. If there is a deferment on the "Payroll" tab that's held, you may have to delete that so it doesn't *also* happen. It will give you an opportunity to email people with the change. Just send it to yourself.

After adding a new deferment to AMI, you have to mirror it over in Gusto. To do so, pull up the employee, go to their Benefits tab, and add it. That should do it. 


### Calculating deferments

There is a spreadsheet — "ira-contribution-master-file.xlsx" — with all of the contribution amounts in the HR folder. Add the employee's compensation there to calculate the 3% match. Remember, it's a match of their contribution up to 3% of their compensation. The spreadsheet has a calculator for this. 


[simple]: https://www.irs.gov/retirement-plans/plan-sponsor/simple-ira-plan
[irs-cr]: https://www.irs.gov/retirement-plans/plan-participant-employee/retirement-topics-simple-ira-contribution-limits

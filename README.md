<h1 align="center">Prajjwal Ujjaini</h1>

<p align="center">
  <b>Flutter Web engineer · Indore, India</b><br>
  I build the apps — and the packages under them.
</p>

<p align="center">
  <a href="mailto:prajjwalujjaini@gmail.com"><img src="https://img.shields.io/badge/email-prajjwalujjaini%40gmail.com-0F6E56?style=flat-square&logo=gmail&logoColor=white"></a>
  <a href="https://pub.dev/publishers"><img src="https://img.shields.io/badge/pub.dev-seat__kit%20%C2%B7%20invoice__kit-5F30BA?style=flat-square&logo=dart&logoColor=white"></a>
  <img src="https://img.shields.io/badge/Flutter-Web%20first-1FA37B?style=flat-square&logo=flutter&logoColor=white">
</p>

---

### What I'm working on

I'm building an event management ecosystem at **CityEvent Dynamic Pvt Ltd** — three Flutter Web apps sharing one design system and five internal packages.

| | |
|---|---|
| **Amantran India** | Consumer app for digital invitations, bookings and payments. Migrated the whole codebase from GetX to Riverpod without pausing feature work. |
| **Organiser dashboard** | Where organisers manage listings, seating and invoices. |
| **Ops console** | Internal crew tool — approvals, payments, tickets. Invite-only, phone-OTP. |

### How it's layered

```
apps      amantran_india · organiser_app · admin_app
                        ↓
kits      auth_kit · theme_kit · invoice_kit · seat_kit
                        ↓
core      core_kit  — no Riverpod, no UI, no business logic
```

Dependencies only point downward. Kits declare interfaces, apps inject the implementations. No package knows about a plan, a price, or a business rule.

### On pub.dev

- **seat_kit** `v0.2.0` — seat map rendering and selection for venues and events
- **invoice_kit** `v0.1.0` — invoice models, tax handling and PDF-ready layouts

### Tools I reach for

`Flutter Web` `Dart` `Riverpod 3` `flutter_hooks` `Freezed` `Beamer` `Dio`
`ThemeExtension` `Spring Boot APIs` `Razorpay` `GitHub Actions` `AWS`

### Reach me

📧 prajjwalujjaini@gmail.com &nbsp;·&nbsp; 📱 +91 74159 68218

<!--
Add these two lines back once you're happy with the stats cards:
![](https://github-readme-stats.vercel.app/api?username=Prajjwal-Ujjaini&show_icons=true&theme=dark&hide_border=true&bg_color=0C1310&title_color=1FA37B&icon_color=8B5CF6)
![](https://github-readme-stats.vercel.app/api/top-langs/?username=Prajjwal-Ujjaini&layout=compact&theme=dark&hide_border=true&bg_color=0C1310&title_color=1FA37B)
-->

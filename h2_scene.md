# a) Podcast Summary

## Darknet Diaries Podcast: Synthetic Remittance from September 20, 2022
https://open.spotify.com/episode/5M4ghNl16ZA3Cnx41KWQRy?si=2ead39bbfa874caf
*What do you get when you combine social engineering, email, crime, finance, and the money stream flowing through big tech? Evaldas Rimašauskas comes to mind. He combined all these to make his big move. A whale of a move.*

**Who:** Evaldas Rimasauskas, a Lithuanian national.

**When:** From 2012 – 2015; convicted in 2019.

**Targets:** Facebook and Google, but main focus in the Podcast is on Facebook

**What:** Sent fraudulent invoices, contracts, and letters to Google and Facebook employees, impersonating the real supplier stealing 98 million USD from Facebook and 23 million USD from Google

**Methods:** Social engineering, Business email comprimise (BEC), Forgery, Wire Fraud

### How it happened
- Evaldas and his team **Used social engineering** through **many contacts over a longer period of time** to collect bits and pieces of information, starting from making regular customer service calls asking innocent questions about how the company paid bills, for example by pretending to be publically known contractors, or contacting publically known contracters.
- As they got more information, they could ude the information to get more information from people higher up in the chain, and so on and so on.
- Over time, this gave them all **the needed knowledge** about the **internal processes and company structure** related to accounting and paying bills, and **identified the relevant people and their contact info** and developed their insight of the internal **social structures**
- They **identified a specific supplier** who Facebook frequently would pay invoices to - Quanta Computer, Taiwan, from public information 
- They **created a fake company** registered in Latvia **with the same name** as Quanta Computer, and registered a **similar domain**
- Got access to a **real invoice** from Quanta Computer to Facebook, and forged one like it with the fake company's account information
- Used **spoofed email addresses** that closely resembled legitimate ones to ask for payment of the fraudulent invoices
- After they succesfully did this to Facebook, they foundout that Quanta Computer was also a suppler of Google, and simply used the same Social engineering + BEC approach to succesfully steal money from Google in the same way.
  
### End Game
- Despite extensive efforts transfering the money around to avoiding a tracking, Evaldas was captured due to a basic mistake. He used his own personal email to register the similar domain used for the BEC.
- He got sentenced to five years in prison and a fine of 26 million USD
- Not known what haoppened to his co-conspiritors
- With government help Facebook and Google managed to get most of the lost money back

### Takeaways
- Even large companies can get hit, by very small teams
- BEC scams like this are not new, and remain a common attack
- Some technical action could be done to avoid this, like tools that automatically recognize/block e-mails from lookalike/new/false domains
- Cyber security is everyones responsibility

# b) Blog Article Summary
Darknet Diaries
Episode 159 Vastaamo
https://open.spotify.com/episode/2GrOQ1x3KKPStBhpTKlpFx?si=8ef919b040ac4f47

Vastaamo was a Finnish private psychotherapy company that managed therapy records for tens of thousands of clients across Finland.
In October 2020, it was revealed that the company had been hacked, and highly sensitive patient therapy notes and personal data were stolen — including mental-health diagnoses, session summaries, and contact details.
The attackers began blackmailing both the company and individual patients, demanding Bitcoin payments to prevent their private therapy notes from being published on the dark web.
Some patient records were indeed leaked publicly when ransoms were not paid.

Investigations showed that Vastaamo’s database was left exposed to the internet without proper authentication for long periods (as early as 2018).
The system stored unencrypted sensitive data, and logs suggested the intrusions had gone undetected for years.
The breach likely occurred between 2018 and 2019, but the company failed to disclose it promptly — possibly due to internal mismanagement and lack of security awareness.
This delay later became a legal issue, as the company’s management was accused of negligence and cover-up.

Impact
Over 30,000 Finnish citizens were directly affected, making it one of the largest data breaches in Finland’s history.
Victims faced psychological distress, social stigma, and secondary blackmail, as leaked notes contained intimate therapy content.
The Finnish government established free crisis support services and even new legislation to improve health data protection.
Vastaamo ultimately went bankrupt in 2021.
The CEO at the time of the breach, Ville Tapio, was convicted in 2023 for data protection crimes due to failure to secure sensitive data and report the breach.

Used spoofed email addresses that closely resembled legitimate ones.
Convinced the companies to transfer large payments to bank accounts he controlled in Latvia, Cyprus, and elsewhere.
Amount stolen: Around $100 million USD total.

Capture: Arrested in Lithuania (2017) after U.S. indictment; extradited to the United States.

Outcome:

Pleaded guilty to wire fraud in 2019.

Sentenced to 5 years imprisonment and ordered to forfeit $49.7 million.

Significance:

- Showed that even top tech companies can fall victim to simple social-engineering and invoice scams.
- Highlighted weaknesses in financial verification and internal control processes.
- Became a textbook example of BEC attacks in cybersecurity awareness training and fraud-risk management.
In April 2024, Finnish police arrested a suspect in France, a Finnish man named Julius Kivimäki, who was later extradited and convicted in 2025 for the blackmail and hacking crimes.

The case triggered major reforms in Finland’s data-protection practices, highlighting the need for cybersecurity in healthcare.

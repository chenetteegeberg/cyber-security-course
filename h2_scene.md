# a) Darknet Diaries Podcast Summary: Synthetic Remittance 
*"What do you get when you combine social engineering, email, crime, finance, and the money stream flowing through big tech? Evaldas Rimašauskas comes to mind. He combined all these to make his big move. A whale of a move."*  

Episode 124 from September 20, 2022 by Jack Rhysider 

https://open.spotify.com/episode/5M4ghNl16ZA3Cnx41KWQRy?si=2ead39bbfa874caf 

## What happened
This podcast is about an attack on Facebook and Google that took place from 2012 to 2015, where Evaldas Rimasauskas sent fraudulent invoices to Google and Facebook employees, impersonating a real supplier and sucessfully stealing 98 million USD from Facebook and 23 million USD from Google.

**Methods:**
- Social engineering, Business email comprimise (BEC), Forgery, Wire Fraud

## How it happened

- Evaldas and his team **Used social engineering** through **many contacts over a longer period of time** to collect bits and pieces of information
- They started by making regular customer service calls asking innocent questions about who to contact or how bills were paid, for example by pretending to be publically known contractors, or contacting publically known contracters.
- As they got more information, they could use the information to get more information from people higher up in the chain, and so on and so on.
- Over time, this gave them all **the needed knowledge** about the **internal processes and company structure** related to accounting and paying bills, and **identified the relevant people and their contact info** and developed their insight of the internal **social structures**
- They **identified a specific supplier** who Facebook frequently would pay invoices to - Quanta Computer, Taiwan, from public information 
- They **created a fake company** registered in Latvia **with the same name** as Quanta Computer, and registered a **similar domain**
- Got access to a **real invoice** from Quanta Computer to Facebook, and forged one like it with the fake company's account information
- Used **spoofed email addresses** that closely resembled legitimate ones to ask for payment of the fraudulent invoices
- After they succesfully did this to Facebook, they foundout that Quanta Computer was also a suppler of Google, and simply used the same Social engineering + BEC approach to succesfully steal money from Google in the same way.
  
## End Game
- Despite extensive efforts transfering the money around to avoiding a tracking, Evaldas was captured due to a basic mistake. He used his own personal email to register the similar domain used for the BEC.
- He got sentenced to five years in prison and a fine of 26 million USD
- Not known what haoppened to his co-conspiritors
- With government help Facebook and Google managed to get most of the lost money back

## Takeaways
- Even large companies can get hit, by very small teams
- BEC scams like this are not new, and remain a common attack
- Some technical action could be done to avoid this, like tools that automatically recognize/block e-mails from lookalike/new/false domains
- Cyber security is everyones responsibility

# b) Blog Article Summary: Why Take9 Won't Improve Cybersecurity

*"The latest cybersecurity awareness campaign asks users to pause for nine seconds before clicking — but this approach misplaces responsibility and ignores the real problems of system design."* 

Blog post from May 28, 2025 by Bruce Schneier, Arun Vishwanath 

https://www.darkreading.com/cybersecurity-operations/why-take9-will-not-improve-cybersecurity

The blog post is about the Take9 cyber security awareness campaign, which tells users to pause for nine seconds before taking online actions.

## Main points
- The authors argue that Take9 won’t make people or systems safer, because it asks users to fix a problem that comes from poor system design, not lack of patience.
- They highlight that this kind of advice is not realistic — no one can pause that long hundreds of times a day and that similar ideas like “Stop. Think. Connect.” have already failed in the past.
- They say that problem isn’t that people act too fast, but that they don’t have enough knowledge or context to tell what’s safe and what isn’t.
- The authors refer to the SCAM model (Suspicion, Cognition, Automaticity) — showing that real awareness requires helping people understand risks, not just telling them to pause 
- They also highlight that modern phishing and scams are so advanced that even experts can be fooled, so no one can be perfectly trained to resist.
- And people cannot be expected to check everything themselves — just like we don’t check airplane engines before flying or restaurant kitchens before eating.

## Conclusive message
- The authors argue that cybersecurity should not blame users for bad system design
- People cannot be expected to check everything themselves — just like we don’t check airplane engines or restaurant kitchens before use.
- Instead they refer to what security researcher Angela Sasse first said in 1999: "Users are not the enemy."
- Real security improvement needs better system design, clearer safeguards, and policies that protect users, not campaigns that make them feel responsible for failures.

# c) Application of theories/models

## Social engineering and manipulation
The attack on Google and Facebook worked by manipulating people, not systems. 
- Mitnick described social engineering as the art of manipulating people into doing things or giving away information.
- Mitnick’s model of social engineering describes four steps: research, building trust, exploitation and exit. Evaldas followed these steps exactly.

## Awareness and system design
The case also shows that awareness alone could not prevent the deception because controls and cognitive support were missing.
- In the Take9 article, the authors refer to the SCAM model (Suspicion, Cognition, Automaticity), explaining that users can be trained to notice unusual things but cannot be responsible for every decision.
- This links with the principle from Angela Sasse and Anne Adams (1999) — “Users are not the enemy.” an that users should be treated as partners in security design, not blamed when systems fail.
https://cacm.acm.org/research/users-are-not-the-enemy/

## AI increases threat from modern social engineering
- Schmitt & Flechais (2024) conduct a systematic review of social engineering and AI capabilities and use a theory of social engineering to identify three pillars where Generative AI amplifies the impact of social engineering attacks
- They explored how generative AI makes social engineering stronger through fake but realistic content, advanced targeting and automated attacks.
- This demonstrates the limitations of awareness-only campaigns and the growing need for holistic security that combines people, processes, and technology.

## Conclusion cyber security protection must be holistic
The attack clearly shows why all three areas of cybersecurity, technology, people, and processes, need to work together. 
- Even technically advanced companies can be vulnerable when internal processes and policies fail. 
- There are technological protections that could help prevent such attacks today, but in reality, technology alone will never be enough, because the goalpost is always moving.
- For the same reason, people cannot know everything. Employees can be trained to be more suspicious (SCAM model) and aware of risks, but they cannot be expected to catch every threat, especially now when AI makes fake content, messages, and identities look more convincing than ever.
Consequently, effective cybersecurity requires designing systems, policies, and processes that support human awareness and reduce opportunities for manipulation.

# Sources

Blog post from May 28, 2025 by Bruce Schneier, Arun Vishwanath: Why Take9 Won't Improve Cybersecurity. https://www.darkreading.com/cybersecurity-operations/why-take9-will-not-improve-cybersecurity

Darknet Diaries Podcast Episode 124 from September 20, 2022 by Jack Rhysider: Synthetic Remittance. https://open.spotify.com/episode/5M4ghNl16ZA3Cnx41KWQRy?si=2ead39bbfa874caf 

Schmitt, M., & Flechais, I. (2024). Digital deception: Generative artificial intelligence in social engineering and phishing. The Artificial intelligence review, 57(12), 324. https://doi.org/10.1007/s10462-024-10973-2. https://link.springer.com/article/10.1007/s10462-024-10973-2 

Lopes, A., Mamede, H. S., Reis, L., & Santos, A. (2024). Common Techniques, Success Attack Factors and Obstacles to Social Engineering: A Systematic Literature Review. Emerging science journal, 8(2), 761-794. https://doi.org/10.28991/ESJ-2024-08-02-025. https://doaj.org/article/c67ded3092f54e96a942209c1d404cdc

Adams, A., & Sasse, M. A. (1999). Users are not the enemy. Communications of the ACM, 42(12), 40-46. https://doi.org/10.1145/322796.322806. https://cacm.acm.org/research/users-are-not-the-enemy

Mitnick Security: The History of Social Engineering. https://www.mitnicksecurity.com/the-history-of-social-engineering

# We finally know what caused the global tech outage - and how much it cost

Published :`2024-07-25 09:17:06`

---

Insurers have begun calculating the financial damage caused by last week’s devastating CrowdStrike software glitch that crashed computers, canceled flights and disrupted hospitals all around the globe — and the picture isn’t pretty.

What’s been described as the largest IT outage in history will cost Fortune 500 companies alone more than $5 billion in direct losses, according to one insurer’s analysis of the incident published Wednesday.

The new figures put into stark relief how a single automated software update brought much of the global economy to a sudden halt — revealing the world’s overwhelming dependence on a key cybersecurity company — and what it will take to recover.

The estimates come the same day that CrowdStrike issued a preliminary report on how it inadvertently caused the widespread IT meltdown. It is the most detailed technical analysis to date of the outage.

Businesses are scrambling to recover – especially Delta Air Lines. Delta is still dealing with fallout from the glitch, as thousands of flights have been canceled. The Department of Transportation is investigating.

Numerous Fortune 500 companies use CrowdStrike’s cybersecurity software to detect and block hacking threats. But when CrowdStrike issued an update last week to its signature cybersecurity software, known as Falcon, millions of computers around the world running Microsoft Windows crashed because of the way that the update interacted with Windows.

The health care and banking sectors were the hardest hit by CrowdStrike’s mishap, with estimated losses of $1.94 billion and $1.15 billion, respectively, said Parametrix, the cloud monitoring and insurance firm behind Wednesday’s analysis.

Fortune 500 airlines such as American and United were the next most affected, losing a collective $860 million, Parametrix said.

All told, the outage may have cost Fortune 500 companies as much as $5.4 billion in revenues and gross profit, Parametrix said, not counting any secondary losses that may be attributed to lost productivity or reputational damage. Only a small portion, around 10% to 20%, may be covered by cybersecurity insurance policies, Parametrix added.

Fitch Ratings, one of the largest US credit ratings agencies, said Monday that the types of insurance likely to see the most claims stemming from the outage include business interruption insurance, travel insurance and event cancellation insurance.

“This incident highlights a growing risk of single points of failure,” Fitch said in a blog post, warning that such single points of failure “are likely to increase as companies seek consolidation to take advantage of scale and expertise, resulting in fewer vendors with higher market shares.”

The eye-popping damage estimates underscore how a preventable mistake at one of the world’s most dominant cybersecurity firms has had cascading effects for the global economy — and may prompt more calls for CrowdStrike to be held accountable.

### What went wrong

On Wednesday, CrowdStrike released a report outlining the initial results of its investigation into the incident, which involved a file that helps CrowdStrike’s security platform look for signs of malicious hacking on customer devices.

The company routinely tests its software updates before pushing them out to customers, CrowdStrike said in the report. But on July 19, a bug in CrowdStrike’s cloud-based testing system — specifically, the part that runs validation checks on new updates prior to release — ended up allowing the software to be pushed out “despite containing problematic content data.”

The bad release was published just after midnight Eastern time on July 19, and rolled back an hour and a half later, at 1:27 a.m. Eastern, CrowdStrike said. But by then millions of computers had already automatically downloaded the faulty update. The issue affected only Windows devices, not Mac or Linux machines, and only those that were switched on and able to receive updates during those early morning hours.

Thanks to the timing of the incident, organizations in Europe and Asia “had more of their work day affected by the outage, unlike the Americas,” Fitch wrote in its blog post.

When Windows devices using CrowdStrike’s cybersecurity tools tried to access the flawed file, it caused an “out-of-bounds memory read” that “could not be gracefully handled, resulting in a Windows operating system crash,” CrowdStrike said.

That’s the Blue Screen of Death that many people reported seeing on their machines, and that only a manual intervention to delete the bad file could fix — a slow, painstaking process when you consider that as many as 8.5 million individual devices will need to be reset this way.

That figure is small as a percentage of the wider Windows ecosystem, said Microsoft — a company that played no direct role in the outage. Still, Microsoft said in a blog post, it “demonstrates the interconnected nature of our broad ecosystem.”

CrowdStrike said that the testing and validation system that approved the bad software update had appeared to function normally for other releases made earlier in the year. But it pledged Wednesday to keep software glitches like last week’s from happening again, and to publicly release a more detailed analysis when it becomes available.

The company added that it is developing a new check for its validation system “to guard against this type of problematic content from being deployed in the future.”

And CrowdStrike said it also plans to move to a staggered approach to releasing content updates so that not everyone receives the same update at once, and to give customers more fine-grained control over when the updates are installed.

CNN’s Sean Lyngaas contributed to this report

---


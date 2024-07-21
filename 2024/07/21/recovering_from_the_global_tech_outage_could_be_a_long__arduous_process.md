# Recovering from the global tech outage could be a long, arduous process

Published :`2024-07-21 12:27:32`

---

The company that caused a massive computer outage across the world says a flawed update has been rolled back – but that doesn’t necessarily help the thousands of businesses that have been affected by the glitch.

The CrowdStrike software issue at the heart of the outage runs at such a deep level in affected computers and systems that getting them up and running just to be fixed will be, in many cases, an enormous challenge.

That’s compounded by the fact that many of the servers that may contain information needed to get these systems working again are themselves caught in a cycle of crashing and rebooting.

And some affected computers might not even be easily accessible, set up in remote locations and intended to run without human intervention.

“I don’t think it’s too early to call it: this will be the largest IT outage in history,” said security expert Troy Hunt in a post on X.

The CrowdStrike software at fault operates at what’s called the kernel level of a computer, a much deeper level than what more ordinary applications such as browsers or video games do. This portion of a device has much greater visibility and control over a computer and its components, making it critical for the operation of all other systems — and far more sensitive.

Running at the kernel level means CrowdStrike’s software can do more to detect cyberattacks, but it also means the current bug is causing Windows computers to crash to a Blue Screen of Death before users can take any actions to correct it.

The issue appears to be recoverable, CrowdStrike has said, but in many cases it requires painstaking work: Each affected device must be accessed by an administrator and manually rebooted into safe mode. Then, the offending CrowdStrike file must be deleted by hand.

For businesses with hundreds or thousands of laptops, desktops and servers running CrowdStrike’s security software, an individual human may have to perform that process over and over and over again.

“You can’t automate that,” said Kevin Beaumont, a security researcher and former Microsoft threat analyst, in a post on X. “So this is going to be incredibly painful for CrowdStrike customers.”

On Friday, a Microsoft status page reported that some Windows Virtual Machine users have successfully recovered from the issue by repeatedly rebooting, in some situations up to 15 times in a row.

“We have received feedback from customers that several reboots (as many as 15 have been reported) may be required, but overall feedback is that reboots are an effective troubleshooting step at this stage,” Microsoft said on the page. The company did not speculate as to why the technique appears to work.

Affected organizations can also try to restore their machines to an earlier state by reverting to a previous system backup, Microsoft added, though it acknowledged that may not be possible in all cases.

“Companies that haven’t invested in rapid backup solutions are stuck in a catch-22,” said Eric O’Neill, a cybersecurity expert and former FBI counterintelligence official.

It gets worse.

Organizations that take security seriously will have likely encrypted their computers’ hard drives, making it even more challenging to access the file that needs to be deleted.

For those organizations, “you need to manually decrypt the disk with a BitLocker Recovery Key, which is probably — for most companies — stored digitally on one of the servers that is currently booting over and over,” said Ira Bailey, a security researcher, in a post on BlueSky.

Every affected computer that is BitLocker-encrypted will need to be unlocked with a recovery key before organizations can begin the process of deleting the bad CrowdStrike file and restoring normal operation, said the cybersecurity expert who goes by the pseudonymous handle SwiftOnSecurity in a post on X.

Recovery will be enormously expensive for Fortune 500 companies with large teams of IT staff and likely even more challenging for smaller firms, Kenn White, an independent security researcher who specializes in network security, told CNN.

“If you don’t have physical staff that can actually touch it, this is going to take many, many days for much of corporate America to recover from,” White said. “It’s just a ton of labor-intensive manual work.”

“It’s a fairly complicated procedure for non-technical people,” White added, “and even a lot of skilled IT professionals will find it difficult to do this at the scale that’s going to be required given the number of machines that are affected.”

### How did the CrowdStrike bug lead to such widespread effects?

Because CrowdStrike’s security software is running on countless individual computers all around the globe, the update that got pushed to those devices caused them all to shut down, virtually simultaneously.

And in today’s networked economy, an outage in one part of a supply chain can cause  domino effects up and down the line. When multiple parts of a supply chain go down, it touches off a cascade of problems.

Imagine a person trying to buy a coffee, said Andrew Peck, a cybersecurity expert at Loughborough University in the UK. What may seem like a simple transaction relies on multiple computers working in tandem, from the coffee shop’s point of sale to the payment processor’s own back-end systems.

“There are a lot of computers in this chain, and usually the larger the business, the larger the chain,” Peck said. “If any one of the computers are down in the chain, the transaction will not complete.”

It could take millions of person-hours of work by corporate IT professionals to fix all the computers that were affected, said O’Neill, the former FBI counterintelligence operative. But, he said, coming up with a firm estimate is difficult because it’s unknown how many computers were affected.

Imagine something like the massive aviation industry, the critical financial services sector or the life-or-death operations of a health care provider, and the scope of the disaster becomes starkly clear.

With many people now working from home, he said, IT professionals can’t just go desk-to-desk to fix different computers. Instead, they’ll have to communicate with individual employees and talk them through the process remotely.

“That magnifies the issue,” he said. “Something that could have been fixed in hours is going to take days.”

Some affected machines may be rarely serviced by people or located in remote areas. Others may not even have monitors or keyboards plugged in, because they don’t regularly require humans to directly interact with them.

The most extreme examples may include weather monitoring sensors or devices in railway signal boxes, Peck said, which could require technicians to physically visit potentially hundreds of thousands of machines to perform the recovery process.

Recovery will cost the world “thousands of hours and millions, potentially billions of dollars,” Peck said, which quickly adds up to “some very exhausted IT support teams burning budget they didn’t have.”

### What is Microsoft’s role in all this?

A separate issue earlier, on Thursday, did lead to significant impacts on many of Microsoft’s own cloud customers, but it was resolved overnight and was unrelated to the CrowdStrike issue, Microsoft and multiple cybersecurity experts told CNN.

The CrowdStrike bug may have initially been conflated with the Microsoft issue because CrowdStrike’s error affected only Windows machines.

“Both are Microsoft-related, but Microsoft had nothing to do with the second incident,” White told CNN.

That appears to be supported by Microsoft’s own status account on X, which on Thursday announced an issue affecting “Microsoft 365 apps and services” and a separate announcement Friday addressing the CrowdStrike outage. The two issues are being tracked using different reference numbers.

As of Friday morning, Microsoft said the issue with Microsoft 365 had been resolved and that the situation was improving.

“The ongoing CrowdStrike issue is unrelated to a previous outage in the Central US Azure region on July 18, impacting Azure customers using that region as well as some Microsoft 365 services,” Microsoft said.

Microsoft CEO Satya Nadella acknowledged the CrowdStrike issue in a post on X Friday morning, saying Microsoft is “working closely with CrowdStrike and across the industry to provide customers technical guidance and support to safely bring their systems back online.”

Since the update to CrowdStrike’s software was delivered by the company’s own systems, it appears unlikely that Microsoft bears direct responsibility for Friday’s outages, said Beaumont, who said he reviewed a copy of CrowdStrike’s flawed update.

The problem with CrowdStrike’s update was that it wasn’t formatted correctly “and causes Windows to crash every time,” Beaumont posted on X.

CNN’s Olesya Dmitracova and Chris Isidore contributed reporting.

This story has been updated with additional context and developments.

---


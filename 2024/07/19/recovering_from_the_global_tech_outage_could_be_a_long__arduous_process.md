# Recovering from the global tech outage could be a long, arduous process

Published :`2024-07-19 15:36:42`

---

The company that caused a massive computer outage across the world says a flawed update has been rolled back – but that doesn’t necessarily help the thousands of businesses that have been affected by the glitch.

The CrowdStrike software issue at the heart of the outage runs at such a deep level in affected computers and systems that getting them up and running just to be fixed will be, in many cases, an enormous challenge.

That’s compounded by the fact that many of the servers that may contain information needed to get these systems working again are themselves caught in a cycle of crashing and rebooting.

“I don’t think it’s too early to call it: this will be the largest IT outage in history,” said security expert Troy Hunt in a post on X.

The CrowdStrike software at fault operates at what’s called the kernel level of a computer, a much deeper level than what more ordinary applications such as browsers or video games do. This portion of a device has much greater visibility and control over a computer and its components, making it critical for the operation of all other systems — and far more sensitive.

Running at the kernel level means CrowdStrike’s software can do more to detect cyberattacks, but it also means the current bug is causing Windows computers to crash to a Blue Screen of Death before users can take any actions to correct it.

The issue appears to be recoverable, CrowdStrike has said, but in many cases it requires painstaking work: Each affected device must be accessed by an administrator and manually rebooted into safe mode. Then, the offending CrowdStrike file must be deleted by hand.

For businesses with hundreds or thousands of laptops, desktops and servers running CrowdStrike’s security software, an individual human may have to perform that process over and over and over again.

“You can’t automate that,” said Kevin Beaumont, a security researcher and former Microsoft threat analyst, in a post on X. “So this is going to be incredibly painful for CrowdStrike customers.”

It gets worse.

Organizations that take security seriously will have likely encrypted their computers’ hard drives, making it even more challenging to access the file that needs to be deleted.

For those organizations, “you need to manually decrypt the disk with a BitLocker Recovery Key, which is probably — for most companies — stored digitally on one of the servers that is currently booting over and over,” said Ira Bailey, a security researcher, in a post on BlueSky.

Every affected computer that is BitLocker-encrypted will need to be unlocked with a recovery key before organizations can begin the process of deleting the bad CrowdStrike file and restoring normal operation, said the cybersecurity expert who goes by the pseudonymous handle SwiftOnSecurity in a post on X.

Recovery will be enormously expensive for Fortune 500 companies with large teams of IT staff and likely even more challenging for smaller firms, Kenn White, an independent security researcher who specializes in network security, told CNN.

“If you don’t have physical staff that can actually touch it, this is going to take many, many days for much of corporate America to recover from,” White said. “It’s just a ton of labor-intensive manual work.”

“It’s a fairly complicated procedure for non-technical people,” White added, “and even a lot of skilled IT professionals will find it difficult to do this at the scale that’s going to be required given the number of machines that are affected.”

This is a developing story. It will be updated.

---


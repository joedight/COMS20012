# Exercises sheet 4

**Correction after reading week.**

## Authentication Methods

1. Explain in your own words what:
* authentication means;
* authorization means;
* accountability means.



2. Pick on of your favourite online services (Google, Twitter, Facebook etc.)
Check and discuss their recovery mechanism.



3. Research on Goolge why SMS recovery is not suitable anymore to protect against targeted attack.
A general audience article from Forbes can be found [here](https://www.forbes.com/sites/zakdoffman/2020/10/11/apple-iphone-imessage-and-android-messages-sms-passcode-security-update/){:target="_blank"}.



4. Building on [Bonneau et al. S&P paper](../materials/lecture4/2012-sp.pdf){:target="_blank"} provided as lecture material. Discuss why it is difficult to replace passwords.


		In comporary time (the paper is nearly 10 years old) you can still see that a lot in there still hold true.
		For example, you are not using biometrics for remote authentication.
		It will be either used to connect locally (e.g., your smartphone) or as part of a two factors authentication scheme to generate a one time code on your smartphone to be used on a website to authenticate.
		The concept behind the paper, and this type of reasoning around security concepts, are quite important.

5. Building on [Bonneau et al. S&P paper](../materials/lecture4/2012-sp.pdf){:target="_blank"} and [Cheon et al. S&P paper](../materials/lecture4/2020-sp.pdf){:target="_blank"} suggest a (simple) framework to compare authentication via pin code and gesture on smartphone.
**Discuss your frameworks within your lab groups**.
You should agree on a lab-group level framework, **be ready to discuss your frameworks during Friday Q&A**.


		The idea is to think of a table equivalent to table 1 in the precedent paper to draw a comparison with pin code approach. Both approaches have draw-back.
		Further, the paper highlight that "free form" passwords may not be as one would naively think.
		This is again to reinforce that authentication is a complex problem that needs to be carefully considered.
		If you enjoy this sort of content and the Computer Society unit, you may want to consider the Year 3 Unit [Security Behaviour](https://www.bris.ac.uk/unit-programme-catalogue/UnitDetails.jsa?ayrCode=22%2F23&unitCode=COMS30038).

## Network Security

1. Can two network interfaces have the same MAC address? Why or why not?



2. Discuss why installing static ARP tables on the machines of a local-area network does not prevent a malicious machine from intercept-ing traffic not intended for it.



3. TCP connections require a lot of overhead, as compared to UDP. Explain why web sites and file transfers are nevertheless typically transmitted over TCP instead of UDP.



4. How is it that a machine of a private network behind a NAT router can make a connection with a web server on the public Internet?



5. Suppose you suspect that your session with a server has been intercepted in a man-in-the-middle attack. You have a key, K, that you think you share with the server, but you might be only sharing it with an attacker. But the server also has a public key, K<sub>P</sub>, which is widely known, and a private secret key, K<sub>S</sub>, that goes with it. Describe how you can either confirm you share K with the server or discover that you share it only with a man-in-the-middle. Also, be sure your solution will not be discovered by a packet sniffer.



6. Explain how a stateless firewall would block all incoming and outgoing HTTP requests.



7. Explain how a port scan might be a preliminary indication that another attack is on its way.



8. Describe the types of rules that would be needed for a rule-based intrusion detection system to detect an ARP spoofing attack.



9. During TLS enabled connection, why do we use DH key exchange for sharing a session key, given the fact that we use a public-key crypto systems that can be used to share the session key?



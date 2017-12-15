# Vehicle to Vehicle Communication Protocol
Vehicle to Vehicle Communication (V2V) 
This a git repo dedicated to open sourcing a communication protocol for vehicle to vehicle communication. The need for an open source communication protocol is motivated primarily by two factors, one unification of a common standard across automotive manufacturers and two the need for maintaining user privacy across these networks. 

The bands for V2V communication protocols in the United States were set aside by congress in 1989 and while the need has been omnipresent, the technology to do so has not been adopted. There are a ton of government proposed solutions and many entrepreneurs out there today being funded for startups in this domain. While increased road safety is the greater good, there is a significant threat in a closed source communication protocol. One the accumulation of user data deprives users of their privacy and two a closed source code makes itself more vulnerable to cyber security threats.

The proposal for this system is a direct vehicle to vehicle limited trust network. Unlike the National Highway Traffic Safety Administration (NTHSA) we do not propose any certificates for normal operations. We propose that instead vehicle information is anonymous and trust is limited between user nodes. The dissemination of private user information and the need for certificates to be limited to emergencies.

Like the NTHSA we will propose a set of packet protocols to be transferred between vehicles but the end goal of this repo is simply a V2V network protocol that manufacturers can feel comfortable adopting. Limiting the exchange of data at such an early stage of development or specifying requirements on that data other than format seems counterintuitive. 

I will post some of the protocol I have been working in the next couple days but contributors are welcome. 

Industry Opinion on V2V Rule Changes
https://www.rcrwireless.com/20170414/policy/industry-weighs-in-on-dsrc-for-v2v-communications-part-1-tag6 
National Highway Traffic Safety Administration
https://www.nhtsa.gov/technology-innovation/vehicle-vehicle-communications

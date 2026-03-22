# Free-Energy-Foundation
Free Software Philosophy with Energy Design Priorities

https://www.fsf.org/campaigns/priority-projects/ This project is not on the FSF high priority site because software is not the penultimate goal of technology. However, this interview provides a good background https://www.youtube.com/watch?v=ucXYWG0vqqk

https://github.com/EI2030/Low-power-E-Paper-OS

Why this?

Free Software today is like an aircraft carrier. What started as a raft on the 386, became a kernel with over 40 million lines of code (as of 6.x). Today you can use Linux on microcontrollers, 64 core processors, but nothing user space with a priority on energy-first design. The purpose of this repository is to explicitly focus on designing a kernel based for a solar powerable mobile device. https://hackaday.io/project/177716-the-libre-autarkic-laptop
This project rejects the mainline kernel philosophy and seeks to make an RTOS such as Zephyr for userspace applications and not IoT. 

<img width="640" height="480" alt="17728049478076500869773489803800" src="https://github.com/user-attachments/assets/45421d01-6de2-4bc8-95eb-ed991eb69030" />

![1772804924508970242237414496981](https://github.com/user-attachments/assets/335bf2e2-bfd4-4e3b-bffe-f83e3596cd3d)


License changed to Gaia Public License- where all code belongs to the earth. I would call it GPL, but to avoid ambiguity with the other GPL, I call it the EPL. 

Q&A's:
--

How should I view the FEF?

You should embrace the FEF with the same enthusiasm computer users had when the 80386 became affordable (or any other major milestone, like a TCP/IP card being added to a computer bay.

How to I develop "free energy" systems?

Nothing is free, but access to energy generation such as portable solar panels would allow nearly unlimited recharging of the computer after acquiring one with a system integrated with photovoltatic managers.

Who can develop a modern and efficient solar powered computer? 

Depending on what is considered "efficient," and how much performance you're seeking from a processor. A 1990s Pentium 1 is solar powerable on 32 and 22nm. Intel and Samsung are IDMs that can produce these chips: https://en.wikipedia.org/wiki/Integrated_device_manufacturer

Nvidia, Apple and other top semiconductors (including the companies mentioned above) could also design a Pentium II & III at 2nm or 3nm, and it would run quite efficiently at a reasonable speed- 300MHz, maybe not 900MHz- at less than 10mW. https://www.techrxiv.org/users/814616/articles/1270555-a-heuristic-method-for-designing-solar-circuits A Pentium II could even be integrated with 64MB of RAM in 4mm^2 at 2nm or 1.8nm/1.4nm and likely consume less than 10mW, if set to 233MHz or so.

But will they manufacture it? Very, very, very unlikely. In fact the Claremont demo by Intel was partly funded by a Department of Energy grant. The main reason for developing the tech, near-threshold voltage, at the time, was to lower power consumption when developed at scale (HPCs with hundreds of thousands of co-processors running- but also globally- billions of processors manufactured routinely include 3-4 Quark processors. So little power the processor can run when the PC is off and plugged in or connected to battery)

https://inavoyage.blogspot.com/2026/01/the-nm10-chipset-backporting-to-pentium.html 

How do you get these ideas/design ideas?

I use all of the available open source information available, as well as industry news sites like semiengineering, Semi-analysis, and various PR releases to analyze industry trends and capabilities. I don't have any superpowers, but if I could imagine one, it would be deluding myself into thinking I have the amount of money Apple or Nvidia have to develop a chip, or even unlimited money, and only then some people might seem to be able to think "what can I build/design with this amount of money?" Likewise, a mathematician is more familiar with infinity. They can theorize a large number without needing to have acquired that number. A Physicist can observe much of the visible universe with a telescope, and make theories about technology on earth. For example the sun is a fusion reactor. A physicist who never looks beyond the geocentric view of the earth might not care much about the sun or the celestial bodies, let alone whether the earth revolves around the sun. So applying that logic to earth, a physicist (or a team of them) were able to hypothesize the building blocks of nuclear fusion, on earth, with a net energy output in 2022. Who says computer science should be limited to hackable downstream products? One should think several steps ahead of the foundries and semiconductor companies. Open source shouldn't be focused on restoring old laptops that can't or shouldn't run Windows 11. Of course there is some benefit in salvaging old technology to "make it new," but open source shouldn't be a poor man's technology subsititute or generic alternative. It can (and sometimes is) a leading edge concept or technology. 

Open source projects (on sites like Hackaday typically repurpose downstream hardware- old or consumer targeted hardware. This is in my opinion, a flawed or limiting view of hardware design. Hardware should not be about accepting whatever a Maker company says "should be" a product to hack. It should encompass the entire imagination of the leading edge's capabilities. When Linus Torvalds picked the 80386 to develop linux in the early 90s, it was already a processor on the market since 1985. It was, however, more advanced than many processors that had available monolithic kernels, with the exception of perhaps BSD.

But there is a K-shaped curve in terms of power consumption- the least powerful chip sold isn't a general purpose processor- it is a microcontroller. So the industry today isn't selling the most advanced and energy efficient processor to the general public. The Quark D2000 theoretically could have been that processor, but it was discontinued in 2019. So the market today is skewed towards relatively power heavy chips with few options for maximum (to the limit of physics) energy optimization (not including next-gen chips like Quantum or Adiabatic processors using Maxwell's Demon).

Also, when the Pentium was released in 1995- 100% of the chip was dedicated to performance, to making the system run at full speed, and no dynamic voltage and frequency scaling. Due to the thermal wall, Silicon today is largely dark (off, or idle), so that it can limit the heat of the chip when running different processors (like video playback or other things not being used). At the same time, there is also a lot of unnecessary overhead that is or can be used for telemetry (with a certainty in the former). Chips today aren't made to the limits of physics optimization, but to policy determinations because the abundance of transitors allows for a majority of the Silicon to be under administrative tendencies. A solar powered chip design would remove or at least de-prioritize these chip bugs/"features" until the processors could be made more widely available to regions without electricity and sold commercially wherever they are wanted. 

The competition of AMD, Intel and x86 clones in the early 90s seemed a lot like healthy competition- they wouldn't risk performance losses by adding a nanny state co-processor (assuming it was a 386 or whatever they had available at the time to make a parallel processor- tech that didn't exist in the mainstream til the early 00s) to read and phone home data since it would probably result in a 30-40% performance loss. Today, multi core chips include 3-4 Quark processors+ likely more that are dedicated telemetry capable processors, running Minix in the Intel Management Engine, and on AMD's Security Processor. The luxury of small nanometers today is a privilege that only big corporations can mask from the consumer. It is not only counterproductive/hostile to user's privacy, it prevents an entire class of processors from being sold because it's much harder to hide a 40% performance penalty under a a pentium 1 chip running at 100% speed, yet being efficient at running the software designed for its era, even modernized with a linux 6 kernel (See Action Retro Youtube channel where he installs Tiny Core Linux on a Pentium with 128MB RAM: https://www.youtube.com/watch?v=sxeRCpg9mfc).

My criticism towards Intel wouldn't be so harsh if they actually sold a solar powered product today. But because information control and surveillance is in their partners' interest, solar powered chips with off-grid WAN networks (like Freifunk or LoRAWAN) are antithetical to the national security state. When I began this project 6 years ago, I had little idea how difficult it would be to get this idea off the ground. The open source community is very dependent on big foundries second hand technology- one should think like them, and wonder what they could do. That is how I think, because I think they could do better, and so can you. 


No additional questions & answers available at this time.

1/13/2024: Updated Gist:
---
Software license page: https://gist.github.com/hatonthecat/129c4da1f11a3a69ac25072d7e834b48

The only alignment in this philosophy is eco-alignment. Contrast with AI, which constantly needs to re-align with anthropic principles. The priorities of AGI and ASI are never in perfect alignment, and the time it takes to realign temporarily is an inefficiency shouldered by externalities.

This open source design may resemble

https://en.wikipedia.org/wiki/Open-source_hardware#Reception_and_impact 

"Further, Vasilis Kostakis et al.[80] have argued that open-source hardware may promote values of equity, diversity and sustainability. Open-source hardware initiative transcend traditional dichotomies of global-local, urban-rural, and developed-developing contexts. They may leverage cultural differences, environmental conditions, and local needs/resources, while embracing hyper-connectivity, to foster sustainability and collaboration rather than conflict.[80] However, open-source hardware does face some challenges and contradictions. It must navigate tensions between inclusiveness, standardization, and functionality.[80] Additionally, while open-source hardware may reduce pressure on natural resources and local populations, it still relies on energy- and material-intensive infrastructures, such as the Internet. Despite these complexities, Kostakis et al. argue, the open-source hardware framework can serve as a catalyst for connecting and unifying diverse local initiatives under radical narratives, thus inspiring genuine change.[80]"

https://www.appropedia.org/Open_Source_Appropriate_Technology

"Criticism
This type of idea is clearly not mainstream and suffers from the same criticisms as open source software. In addition, it has been claimed that the decline of the appropriate technology movement is said to be part of the 'remasculinization' of US after the Vietnam War through the Reagan regime.[12] According to Pursell, AT failed because of the inability to counter advocates of agribusiness, large private utilities, and multinational construction companies. These groups maintained the elitist, narrow and traditional definition of the word 'technology' to forward their interests, and not those of the developing world.[12]" 

https://www.jstor.org/stable/3106707

https://249x.substack.com/p/garbatrage-for-sustainable-robotics

https://dl.acm.org/doi/10.1145/3563657.3596128

https://nadia.xyz/climate-tribes#the-climate-tribes-of-today

"Those in climate tech bring a “disruptor’s mindset” to climate. They can be characterized as mildly reactionary to the eco-globalists, believing that the last two decades of global negotiations have little to show for, and that we can instead move faster and more efficiently through the early-stage private sector – primarily, startups. Some in climate tech still have battle scars from the early 2000s cleantech bubble, but enough time has passed that a new generation is willing to learn from previous lessons and experiment with new opportunities.

Those in climate tech see policy as a means of unlocking innovation, rather than as a primary tool for change. The goal is to remove policy roadblocks, not add more (see, for example, the Institute for Progress’s paper on National Environmental Policy Act (NEPA) reform, which argues that the environmental review process is “slowing down the clean energy transition”). Instead, they focus on innovating through commercial markets.

...While energy maximalists skew more towards the R&D side of technology, climate tech operates more on the commercial side of the pipeline: bringing existing technologies to market. Those in climate tech are always looking for low-hanging fruit, overlooked gaps and points of leverage. The carbon removal initiative Frontier, for example, released a “carbon removal (CDR) gap database”, highlighting major knowledge and innovation barriers to carbon removal."

The ironic thing is that some climate tech is actually heavily R&D, but does involve existing technologies, with the exception that R&D is geared towards optimized energy efficiency, rather than an existing technology. Performance per watt computers, for example, unlocking solar-powerable mobile devices. While commercial pipeline is certainly part of the effort, climate tech is potentially the most disruptive of the tribes, including that of energy maximalists, because climate tech seeks to optimize the performance per energy consumed, rather than encouraging maximum production of energy if the path to that involves expensive maintenance (e.g. nuclear).

![image](https://github.com/hatonthecat/Free-Energy-Foundation/assets/76194453/bcec76ac-525c-481b-9d3e-7e6ef2a3379d)

From Climate Tribes [article](https://nadia.xyz/climate-tribes#the-climate-tribes-of-today) ^

![image](https://github.com/hatonthecat/Free-Energy-Foundation/assets/76194453/1a2b0bde-9347-4e0f-98d2-d4bd9ce47673)
From Climate Tribes [article](https://nadia.xyz/climate-tribes#the-climate-tribes-of-today) ^

"Hard stick in the very center: Not very tasty, but a necessary and oft-unappreciated foundation. This group would work in climate regardless of its trendiness: those with science backgrounds, or in relevant industries like energy or manufacturing. They’re motivated by personal curiosity and desire to solve an (often technical) problem."

The charts above points out that certain "climate tech" (which I consider anything energy efficient) developments are low-hanging fruits, overlooked gaps,and points of leverage to make progress more quickly. I think this is far more true in semi-conductor design such as fabless startups that seek to design more energy efficient chips that do not require large wafer dies, yet offer modular chiplets that allow many low-volume customers. While AI startups overlap in some of these regions, a lot of inefficiencies result in devloping software and hardware for platforms that may not be supported years from now, leading some to question the resource utilizaton of certain datacenters.  

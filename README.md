# BritishGP-Telemetry-Analysis
Analysis of the 2026 British Grand Prix using FastF1, Python, and MATLAB to investigate driver consistency, lap time evolution, and race performance.

Key takeaway: The data reframes the result sheet. Leclerc's box is the tightest of the field, locked in ~93.3–94.3s all race: the mark of a controlled, mistake-free drive to the win. But the fastest car on track wasn't his. Antonelli's rolling average plunges to ~92s mid-race, clearly the strongest pace of anyone out there, before spiking violently back up in the closing laps - the wheel shield failure showing up in real time, right there in the trace. He was arguably driving away with this race before the car took it away from him.

Russell's numbers are rockier than a P2 finish suggests, the widest spread in the group, swinging from 92.6s dips to laps near 95.8s - pointing to a result shaped more by strategy and Safety Car timing than outright rhythm. Norris and Hadjar sit at the other end, with higher medians and wider variance - both spent more of the race recovering ground and racing in traffic further back, rather than controlling their pace from clean air up front like Leclerc.

Consistency won the race. Pace didn't. That gap is exactly what this kind of analysis is built to surface.

Same stack as before: Python (FastF1, Pandas, NumPy) for the data pull, MATLAB for the stats and visualisation. 

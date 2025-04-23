proposal for open source community combat(flight, possibly other) simulator

Project Scope:
- Some way for 3rd party developers to profit off of making high quality modules vetted by the project team.
- Community developed, free and open source modules.   


Scope of gameplay:
- Multiplayer PvPvE, multi-platform, peer to peer multicrew avoiding RTT of server like other sims
- Realistic SAMs like real IADS for functional SEAD/DEAD (similar to skynet, able to hide, network, coordinate with interceptors and AWACS)
- Realistic BVR
- Realistic emulation (not simulation) of radar systems (prebaked RCS, not realtime ray casts, we try to get the same results, but at better frame rates)
- Realistic weapons
- Quick Play auto-generation of missions and assets to fight against


Scope Of Modules:
- Full Fidelity clickable, bindable, VR interactable cockpits
- Varied levels of fidelity for things like FM and systems


Scope Of Engine:
- Multiplayer!
- User login to verify ownership of 3rd party modules
- 60fps minimum for moderate hardware, ideally 100fps+
- Distance based culling and simulation simplification
- Modern graphics (near photorealism, not raytraced though an option to enable it wouldn't be out of the question)
- AI units (no, not that AI.)
- Advanced Mission Editor (import images, Live edit collaboration with other user/s, in-game 'ED user files'-like repository for community-made missions)
- Free, well documented modding framework allowing users to spend more time being creative and not fighting with the engine. (A more advanced SDK could be an option for Serious 3rd party studios)


Rules to achieve the goals:
- NO kernel mode anything.
- NO forced temporal rendering solutions like TAA (optional is fine, but must never be forced)
- NO reliance or force of using fake/generated frames to hit framerate targets. Current solutions would also fall under temporal solutions as they blend frames.
- NO DRM in the core engine. 3rd parties may implement DRM through using proprietary model formats etc to protect their work - The sim project team should accomodate for this and provide help with DRM if necessary. 
- VR performance is NOT the metric to measure performance marks, but should be considered.

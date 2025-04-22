proposal for open source community combat(flight, possibly other) simulator



project scope:
- some way for 3rd party developers to profit off of making high quality modules vetted by the project team.


scope of gameplay:
- multiplayer pvpve, multi-platform, peer to peer multicrew avoiding RTT of server like other sims
- realistic SAMs like real IADS for functional SEAD/DEAD (similar to skynet, able to hide, network, coordinate with interceptors and awacs)
- realistic bvr
- realistic emulation (not simulation) of radar systems (prebaked RCS, not realtime ray casts, we try to get the same results, but at better frame rates)
- realistic weapons
- quick play auto-generation of missions and assets to fight against


scope of modules:
- full fidelity clickable, bindable, vr interactable cockpits
- varied levels of fidelity for things like FM and systems


scope of engine:
- user login for module ownership of 3rd party modules
- 60fps minimum for moderate hardware, ideally 100fps+
- distance based culling and simulation simplification
- modern graphics (near photorealism, not raytraced though an option to enable it wouldnt be out of the question)
- multiplayer
- ai units (no, not that ai.)
- mission editor


Rules to acheive the goals:
- NO kernel mode anything.
- NO forced temporal rendering solutions like TAA (optional is fine, but must never be forced)
- NO reliance or force of using fake/generated frames to hit framerate targets. Current solutions would also fall under temporal solutions as they blend frames.
- VR performance is NOT the metric to measure performance marks, but should be considdered.

This anonymised composite case reflects the conditions of a typical UK seaside hotel during the summer holiday period.

I managed the IT systems for a 108-room independent hotel near Brighton. The property included five guest floors, two function rooms, a breakfast hall, a bar, and a sea-facing terrace. During an ordinary weekday, the network appeared acceptable. The trouble arrived when occupancy passed 90 percent.

It did not arrive randomly.

At around 3 p.m., newly arriving guests struggled with the login page. At breakfast, phones and tablets in the dining area connected slowly. After 8 p.m., complaints moved upstairs. Video calls froze, streaming stopped, and several rooms at the ends of the corridors lost usable connections.

Management described the problem as “too many guests.” That explanation was convenient but incomplete. The network was not counting guests. It was handling phones, tablets, laptops, smart televisions, staff terminals, card-payment devices, cloud backups, and guest-service applications.

One occupied family room sometimes placed seven devices on the network. During the busiest evening, we recorded more than 570 connected devices. The hotel had originally been planned around room count, not concurrent device behaviour.

Our existing system had 18 older access points and a 500 Mbps internet connection. Some APs served guest rooms, corridors, and public areas at the same time. Several radios were operating on overlapping channels, while transmit power had been increased in an attempt to solve weak-room complaints. That created stronger signal readings but more radio contention.

The captive portal was another weak point. Between 3 p.m. and 5 p.m., dozens of guests attempted to join at once. The portal occasionally failed to redirect properly, so guests blamed the WiFi even when their room had adequate signal.

We contacted a UK network integrator, who asked COMFAST engineers to review the floor plans, complaint records, AP client counts, WAN usage, and login data. The engineers did not treat the property as one large coverage area. They divided it into guest floors, reception, dining space, function rooms, staff systems, and the outdoor terrace.

This is the purpose of peak-season [peak-season hotel WiFi planning](https://wifioem.com/why-hotel-wifi-fails-during-peak-season-9-causes-and-fixes/) : to identify which layer fails first under realistic occupancy instead of assuming that every problem requires the same upgrade.

The review found several connected faults. The internet circuit regularly exceeded 90 percent utilisation during evening demand, so bandwidth was part of the problem. However, increasing the circuit alone would not have fixed overloaded APs, weak corner rooms, poor channel use, or the failing login flow.

The hotel therefore approved a staged project.

The first phase covered one guest floor, reception, and the breakfast hall. COMFAST WiFi 6 ceiling access points replaced the oldest units. Selected rooms behind bathroom blocks received in-wall APs. A managed PoE switch supported the new deployment, and an AC gateway provided central status and configuration control.

COMFAST engineers worked remotely with the integrator to adjust 2.4 GHz and 5 GHz channels, reduce unnecessary power overlap, review client distribution, and simplify the guest login process. The hotel also separated guest, staff, payment, and management traffic.

After a two-week trial, the hotel approved the full order:

28 ceiling-mounted WiFi 6 access points
10 in-wall access points
2 outdoor access points for the terrace
3 managed PoE switches
1 AC gateway
Backup units and installation accessories

The internet circuit was upgraded from 500 Mbps to 1 Gbps, but only after measurements showed that the existing line was genuinely reaching its limit.

COMFAST then provided a remote training session for the hotel’s IT staff, duty managers, and integrator. Staff learned to distinguish a bandwidth problem from AP overload, a weak room, a PoE failure, or a captive-portal fault.

During the following August bank-holiday weekend, occupancy reached 97 percent. The network carried more than 600 devices at peak time. Check-in authentication remained stable, the breakfast hall no longer affected guest-room performance, and the repeated evening complaint pattern disappeared.

Peak season had not created nine separate accidents. It had exposed several old weaknesses at the same time.

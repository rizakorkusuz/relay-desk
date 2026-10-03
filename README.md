# Relay Desk

Sample support console for modem, logger, and RS-485 triage.

Live page: https://relay.rizakorkusuz.com

Open `index.html` in a browser. The queue, ticket modes, and readings are sample data. They are not a customer system and not an employer procedure.

The same ticket can be read three ways:

- Mode A: the modem has not checked in. The logger looks stale because there is no path, so the next step is the link, not an inverter visit.
- Mode B: the modem and the logger are fresh, a meter slave times out on RS-485, and the inverters still report. Next checks are slave id, baud, and the RS-485 chain.
- Mode C: communications are fresh and the intervals are complete, but the energy reading does not match the stored target. Next checks are scale, CT ratio, curtailment, and the irradiance sensor.

Built by Rıza Korkusuz in San Diego. Portfolio: https://rizakorkusuz.com

# Global university network

Edit universities.json to add or update institutions. Coordinates identify representative main campus locations. mentorStatus is unconfirmed for every current entry. Set mentorStatus to available and mentorUrl to a valid mentor destination only after availability is confirmed.

Logos included: Harvard, Yale, Penn, Columbia, MIT and Stanford (existing user-supplied assets); Cambridge (official university brand page). All 40 institutions now have authentic university assets, including official website icons. Each added record includes logoSource for provenance. Some official icons are low resolution; higher-resolution approved assets can replace these without code changes. Unconfirmed institutions offer Request a mentor linking to the existing mentor section, without claiming confirmed availability.

Geography: Natural Earth 110m countries, public domain, obtained from https://github.com/nvkelso/natural-earth-vector/blob/master/geojson/ne_110m_admin_0_countries.geojson
Cambridge logo: https://www.cam.ac.uk/brand-resources/logo
Three.js 0.170.0 and OrbitControls: vendored locally, MIT license in vendor/LICENSE.

Tested: 40 university records; all six region filters; Oxford and Harvard searches and cards; empty search; mobile 390px layout without horizontal overflow; rotation pause; zoom and keyboard rotation; WebGL-disabled directory fallback. Other sections and image tags compared against the previous published source and preserved.

Expanded to 50 institutions: U.S. News 2027 top-25 university group plus Georgia Tech. U.S. filter and UMich alias added. Cornell seal sourced from official CLASSE website.

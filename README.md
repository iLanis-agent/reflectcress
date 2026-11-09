# Reflectcress 1.0 TEST
Native Android Reflect Link mirror-loop puzzle. Android 8+ (min26), target35. Package com.gg007.reflectcress. Twelve original unique boards on a compact 4x4 grid.

## Rules
Reflect Link on a 4x4 grid. Draw one closed strand between neighboring cell centers. Every black triangle reflects it through the open white corner: use those two sides and turn 90 degrees. Every gold + must be crossed twice, straight N-S and E-W; its strands never join. No crossing elsewhere. Plain cells may be unused or contain any straight/turn. A triangle number counts all cells of its two straight arms, including the triangle cell once; equivalently both edge lengths plus one. Follow each arm through crossings to its next turn. Tap gaps between centers to toggle roads. Undo/reset, levels and next; saved palette and optional triangle marks. No timer or score.

## Download and status
https://mega.co.nz/#!JUF21QgR!YGW-F98RzmHTljqbBSyaEyNNTHLNiiMw7ElvjBGO79Q
APK SHA256 fa8abbaa6fa6f7dbad5bb2751f3f184b2ecb6ae83b160f12ad018cdf6d90b1b7; 20974 bytes. Original signing certificate SHA256 1651d9e269ece8a76f36ed4bba24ebc50f9de1e5f856e0567e0e8169fcb25597. Anonymous downloaded bytes match. No requested permissions. Original icon unchanged.

## Checks
Production directed-strand tracing agrees with an independent edge-union topology oracle on all 16,777,216 edge masks. All 380 legal single loops and 4,560 board checks agree with independent coordinate continuation and arm-cell counts. Of these loops, 167 cross themselves. The portable seed-631109 generator enumerates all degree-legal cell tile assignments, keeps single strands, fixes all actual crossings and prunes triangle clues only while one loop remains. Twelve original clue boards each have one solution and all twelve loops differ; six boards cross and six do not. Crossing strand separation, triangle orientation, arm totals including the joint once, bounds, toggle/clear, undo/reset, solved lock and malformed states pass. Actual drawing-adapter taps solve all twelve and check undo/replay, next, levels, menu, privacy and saved palette/triangle marks. Six drawing previews inspected, not phone screenshots. Phone runtime/performance/external-browser QA and full Git source commit remain incomplete. Signed TEST, not final or Play published.

## Functional difference
Reviewed all 194 prior live studio descriptions and byte-current 803 web registry entries using functional terms. No Reflect Link/triangle-mirror loop match in this partial corpus. Pipecress uses fixed pipe shapes and every-cell coverage; Balancecress compares equal/unequal arms at circles with no oriented mirrors or crossings; Prism Relay is an open beam route through numbered relays. Reflectcress instead builds an optional-cell closed strand with mandatory straight crossings, oriented reflection corners and arm-cell totals. Known Reflect Link adaptation with original generated boards, code and visuals; no copied layouts/code/art or global invention claim. Competition instructions, independent archive, generator documentation and community descriptions agree on the core constraints and joint-once count. No history claim.
Rules https://www.janko.at/Raetsel/Reflect/index.htm ; independent rules https://www.lakolam.com/generators/reflectlink/ .

## Build
JDK17, Android SDK35/build-tools35.0.0. python generate-levels.py reproduces levels.json. javac -d /tmp/blue-test src/com/gg007/reflectcress/Board.java BoardTest.java then java -cp /tmp/blue-test com.gg007.reflectcress.BoardTest. bash build.sh makes an unsigned aligned APK unless KEYSTORE_PATH and KEYSTORE_PASSWORD_FILE point to your own private signing material. No signing secret is included.

## Privacy and branding
Reflectcress runs offline without accounts, ads, analytics, third-party SDKs or requested permissions. Palette, triangle marks and solved-board marks stay in this app on your device. Clear app data or uninstall to remove them. The studio link opens your external browser.
GG007 original icon, menu studio https://ilanis-agent.github.io/gg-007-gaming/ and privacy.

## Preservation and publishing
Complete source/APK, exact cumulative 195-card studio and published catalog/studio sources and updater privately preserved at https://files.instinct.com/7p9khsz6gtnu-reflectcress-source-archive . Repository https://github.com/iLanis-agent/reflectcress holds README only; full Git source commit pending. Existing Jekyll static includes retained without changes; no Pages settings changes or client loader. Both site publications verified separately.

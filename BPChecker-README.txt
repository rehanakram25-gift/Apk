BP CHECKER - ANDROID APP (DEMO PRACTICE ONLY)

What it does
- Floats a small panel on top of the Quotex app (draggable, can be minimised).
- Reads the Quotex chart from the screen (screen-capture permission).
- Finds the candle area, the candles, support/resistance (S/R) lines, the trend and the candle timing by itself.
- Rescans about 3 times a second.
- Checks 20 of your 30 strategies automatically (7, 8, 11, 12, 15, 16, 19, 20, 25, 26 need visual judgement and are skipped).
- About 3 seconds before the next candle opens it shows UP or DOWN (with vibration + beep) when a pattern matches.
- Scores every signal on the next candle and keeps win/loss per strategy ("Scores" button).

HOW TO GET THE APK (no computer needed, but a computer is easier)
1. Make a free account at github.com and create a new repository (any name).
2. Add every file listed in ALL_FILES.txt to the repository:
   Add file > Create new file. Type the path exactly as written after "FILE:" (typing / makes folders),
   paste the content, press Commit. Repeat for all 10 files.
   (On a computer you can instead upload the unzipped folder: Add file > Upload files.)
3. Open the Actions tab > "Build APK" > it runs by itself (or press Run workflow). Wait about 3-5 minutes for a green tick.
4. Open the finished run > Artifacts > BPChecker-APK > download, unzip, open app-debug.apk and install
   (allow "install unknown apps" for your browser/file manager if asked).
5. If the run shows a red cross: open it, copy the error text and send it to Claude. It usually needs one small fix.

HOW TO USE
1. Open BP Checker. Press 1 and allow "display over other apps".
2. Press 2, accept the screen-capture question (Start now).
3. Open the Quotex app on a DEMO account, zoom the chart in so candles are wide.
4. Drag the panel (grab its title) to a spot that does not cover the candles.
5. Wait a few candles. The panel then syncs to the real candle opening time and reads the timeframe from the chart.
   Buttons: Analyze = one-off reading, Sync = manual sync (press exactly when a candle opens), TF = change timeframe,
   Lead = seconds before the candle open (2-5), Scores = per-strategy results, Reset = clear scores.

IMPORTANT LIMITS
- Untested on a real phone: colour/size tuning may be needed. Send photos or screenshots of what the panel shows.
- If Quotex blocks screen capture (black picture), the app cannot read the chart.
- Keep one screen orientation while it runs. If you rotate, stop and start again.
- The signal is read from the last candle while it is still forming, so a last-second move can change it.
- Win rate needs 30+ signals per strategy before it means anything. Break-even at 85% payout is about 54%.

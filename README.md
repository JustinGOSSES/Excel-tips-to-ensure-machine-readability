# Excel-tips-to-ensure-machine-readability
Tips to ensure data manually entered into an excel file is machine readable by other programs later.

1. One piece of information per cell, never more.
2. No commas in data fields ensures can be converted to CSV or read later.
3. No information encoded as color or space or styling. It should be savable as CSV and everything will still all work.
4. Single header row.
5. No hiding columns or rows except as temporary measure.
6. No embedded links or other stuff. Post a link into menu bar instead of cell to avoid excel features that add website title rather than the actual link the user pasted.
7. Put units in headers. Do not add $ in cell, just value in the cell.
8. If data is in multiple sheets, ensure a standardized column exists in both that can enable mapping between.
9. If changes absolutely need to make readable for others, use a new sheet for that that reads data entry sheet via functions.
10. Do sums, averages, etc. on another sheet that calls the data entry sheet. Keep there separate from data sheets.
11. Use another sheet for instructions, definitions, etc. if necessary. Keep these separate from data sheets.

_If these rules aren't followed, there is often time wasted on manual clearning and reorganization to get the data usable by programmatic means.
Following these rules ensures speed and efficiency._

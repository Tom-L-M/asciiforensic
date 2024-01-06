    [ASCII-Forensic-js]
        A JavaScript port of (https://github.com/D4RKW4R3/D4RKW4RE/tree/main)

    Usage:
        asciiforensic.js <mode> [data]

    Modes available:
        -h / --help      -> Shows this help message
        -t / --table     -> Outputs ASCII table to console (suggestion: pipe to file, it is large)
        -s / --scan      -> Manual Analysis: Output chars in different bases
        -a / --autoscan  -> Automatic Analysis: Output chars in different bases, coloring abnormal ones

    Examples:
        script.js -t > asciichars.txt
        script.js -c "some-chars-here"
        script.js -s "some-weird-𐌴har"

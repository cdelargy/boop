    $ pwd
    /Users/me/github/boop

    $ ls
    boop		key.txt		testdata.txt

    $ ./boop
    Usage : boop keyfile sourcefile targetfile
    example: boop abc.txt def.txt xyz.txt

    $ cat key.txt
    A = goeswithA
    B = weirdstuffgoeswithB
    C = moreweirdstuffthatgoeswithC

    $ cat testdata.txt
    B, C, A

    $ ./boop key.txt testdata.txt output.txt

    $ cat output.txt
    weirdstuffgoeswithB, moreweirdstuffthatgoeswithC, goeswithA

how to covfefify a string:
--

###first, get the first sound group (made up terminology): how to do this? well:

find the first vowel (including y):

      v
    creation

find the first consonant after that

        v
    creation
remove the rest of the string

    creat

first sound group

###next step

get the last consonant of the sound group

    t
and replace it with the voiced or voiceless version. to do this, find the letter in this table. replace with the letter given (which may be the same letter)


    b: p
    c: g
    d: t
    f: v
    g: k
    h: h
    j: j
    k: g
    l: l
    m: m
    n: n
    p: b
    q: q
    r: r
    s: z
    t: d
    v: f
    w: w
    x: x
    z: s
so, we get

    d

then, take the next vowel after that consonant. you can assume, that this consonant is not at the end of the string. Join these two together, then repeat them twice

    didi

concatenate this to the first sound group:

    creatdidi

You're done: the string is covfefified, and you can now output it.

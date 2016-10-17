# LiuD_Lesson_1
LiuD lesson one

suppose we have some code like:

    int i = 22
    int j = 3 + i
    int k
    k = i - j
    print(k)

Its syntax can be describe as:

    main = stmt*
    stmt = declare_with_value | declare | assign | funccall
    datatype = 'int' | 'long'
    declare = datatype NAME
    declare_with_value = datatype NAME '=' value
    value0 = NUMBER | NAME
    binvalue = value0 ('+' | '-') value0
    value = binvalue | value0
    assign = NAME '=' value
    funccall = NAME '(' value ')'

We can call this syntax as GDL01 (General Description Language).

Now lets write parse code, in Python 2.x



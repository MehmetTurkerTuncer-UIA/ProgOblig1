# ProgOblig1
------------
Norsk Flagg i https://code.pyret.org/editor
-----------
base-norsk-flag = rectangle(500, 300, "solid", "fire-brick")
white-vertikal = rectangle(80, 300, "solid", "ivory")
white-horistonal = rectangle(500, 80, "solid", "ivory")
blue-vertikal = rectangle(50, 300, "solid", "midnight-blue")
blue-horisontal = rectangle(500, 50, "solid", "midnight-blue")

flag = underlay-xy(base-norsk-flag, 0, 0, # flag variable
 overlay-xy(blue-vertikal, -150, 0,
 overlay-xy(blue-horisontal, 0, -120,
 overlay-xy(white-vertikal, -135, 0,
 overlay-xy(white-horistonal, 0, -105,
 base-norsk-flag)))))

flag  # det kaller variable flag

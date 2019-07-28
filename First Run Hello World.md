import badge
import ugfx

badge.init()
ugfx.init()

ugfx.clear(ugfx.WHITE)

displaytext = "Hello World!"

ugfx.string(0, 0, displaytext,"PermanentMarker36", ugfx.BLACK)

ugfx.flush()

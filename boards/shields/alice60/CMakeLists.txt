zephyr_library()
target_sources(app PRIVATE
  caps_lock_led.c
  )
zephyr_include_directories(include)
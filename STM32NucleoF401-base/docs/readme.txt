to used and build these project user must 

1) have STM32F4_CUBE linked resource variable set and point 
   to stm32f4 cube f/w top directori.

for more detail check note in 
check https://github.com/diabolo38/STM322F4-disco/tree/usbc/ST32F4-Disco/doc  

2) Have/update the link resource CUBE_PROJ_DIR variable   to point to top STM32CubeMX  project folder 
   Use STM32CubeMX to generates code (atollic true studio toolchain)   

trouble shouting

to use debug launch define debug/string substitution variable  (normaly defined by gnu arm eclipse plugin) 
${openocd_path} and ${openocd_executable}
require openocd0.8 (new support for stm32f401 nucleo board)

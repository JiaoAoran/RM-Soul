South China Tigher all rights reserved
Written by 聪明又可爱的小贱狗
Vision 3.0.0
QQ群:512097580
-----------------------------------------------------------------------------------------------------CN-----------------------------------------------------------------------------------------------------
WASD             前后左右移动
QE                  工程/无人机左右旋转
F                     步兵切换单发连发/开启飞镖闸门
G                    开关摩擦轮
Z                     英雄章哥开镜
C                     打开超级电容
Shift[上档]        开启小陀螺
X                     一键掉头
L                     发射飞镖
方向键[↑↓]        无人机起飞和降落
Space[空格]     轮腿跳跃
K[长按]            进入部署模式
L[长按]            退出部署模式
F1                   查看键位
F5                  切换视角(工程和无人机可用)
P                    登出及设置机器人性能
Enter[回车]      打开聊天框(仅可在进入游戏时使用)
Tab                查看得分面板
H                   远程买弹/打开兑矿难度面板
I                     英雄在补给区购买弹丸
O                   步兵在补给区购买弹丸
方向键[↑↓←→] 调整工程末端基于当前视角的位置
UO                工程末端Pitch轴
IM                 工程末端Yaw轴
JK                  工程末端Roll轴
工程的所有操作是基于当前视角的，包括大臂、末端、移动，可通过按两次F5切换第三人称视角，并移动鼠标来改变视角从而在三维空间中调整矿石方向及位置
左键               开火
右键               开启自瞄
鼠标滚轮         英雄章哥大Pitch
---------------------------------------------------------------------------------------------------CMD-CN------------------------------------------------------------------------------------------------
command
进入游戏按Enter[回车]打开聊天框，直接输入可进行聊天，输入以"/"开头的语句可执行指令(仅房主可用)，包括:

//设置经济数量
/**
  * @brief  Sets economic value.
  * @param  camp: battling camps.
  *   This parameter can be one of the Camp enum values:
  *     @arg red: to assign to the red side
  *     @arg blue: to assign to the blue side
  *     @arg spectator: to assign to the both sides
  * @param  Value: set economic value to be assigned.
  *   This parameter can be any positive integer.
  * @retval None
  */
/coin -c Camp -v Value

//重置机器人
/**
  * @brief  Reset the position of robot.
  * @param  Bot: the robot on the field.
  *   This parameter can be one of the Bot enum values:
  *     @arg r1: the hero of red side
  *     @arg r2: the engineer of red side
  *     @arg r3: the infantry of red side
  *     @arg r4: the infantry of red side
  *     @arg r6: the sentinel of red side
  *     @arg r7: the drone of red side
  *     @arg b1: the hero of blue side
  *     @arg b2: the engineer of blue side
  *     @arg b3: the infantry of blue side
  *     @arg b4: the infantry of blue side
  *     @arg b6: the sentinel of blue side
  *     @arg b7: the drone of blue side
  * @retval None
  */
/respawn -r Bot

//获得帮助
/**
  * @brief  Get help of this game.
  * @param  None.
  * @retval None
  */
/help
-----------------------------------------------------------------------------------------------------EN-----------------------------------------------------------------------------------------------------
WASD                         Move in four directions
QE                               Yaw (left/right rotation) of the Drone or Engineer
F                                  Infantry switches between single-shot and burst fire / opens the Dart gate
G                                 Open or close friction wheel
Z                                  Hero 叫我章哥 scope in
C                                  Open Supercapacitor
Shift                             Open spinner
X                                  One-key U-turn
L                                  Lanch Darts
Arrow keys[↑↓]              Drone takeoff and landing
Space                           Balancing Infantry jumping
K[Press and hold]          Enter Hero`s deployment mode
L[Press and hold]          Exit Hero`s deployment mode
F1                                 Check key bindings
F5                                Switch camera view(Engineer and Drone)
P                                  Log out & configure robot performance
Enter                            Open the chat box(Only usable after entering the game.)
Tab                              Check the scoreboard
H                                 Remote projectile purchase / Open the mineral exchange difficulty panel
I                                  Hero purchases projectiles in the resupply zone
O                                 Infantry purchases projectiles in the resupply zone
Arrow keys[↑↓←→]       Adjust the end-effector position of the Engineer robotic arm relative to the current camera view
UO                              Adjust Engineer end-effector Pitch
IM                               Adjust Engineer end-effector Yaw
JK                               Adjust Engineer end-effector Roll
All engineer operations are based on the current camera view, including the arm, end-effector, and chassis movement. Press F5 twice to switch to third-person view, then move the mouse to adjust the camera and thereby reposition and reorient the Ores in 3-D space.
LMB                            Shot
RMB                           Enable auto-aim
Scroll                          Hero 叫我章哥 upper Pitch
---------------------------------------------------------------------------------------------------CMD-EN------------------------------------------------------------------------------------------------
command
Press Enter when you in game to open the chat box, type normally to chat, Commands that start with "/" can be executed only by the host:

/**
  * @brief  Sets economic value.
  * @param  camp: battling camps.
  *   This parameter can be one of the Camp enum values:
  *     @arg red: to assign to the red side
  *     @arg blue: to assign to the blue side
  *     @arg spectator: to assign to the both sides
  * @param  Value: set economic value to be assigned.
  *   This parameter can be any positive integer.
  * @retval None
  */
/coin -c Camp -v Value

/**
  * @brief  Reset the position of robot.
  * @param  Bot: the robot on the field.
  *   This parameter can be one of the Bot enum values:
  *     @arg r1: the hero of red side
  *     @arg r2: the engineer of red side
  *     @arg r3: the infantry of red side
  *     @arg r4: the infantry of red side
  *     @arg r6: the sentinel of red side
  *     @arg r7: the drone of red side
  *     @arg b1: the hero of blue side
  *     @arg b2: the engineer of blue side
  *     @arg b3: the infantry of blue side
  *     @arg b4: the infantry of blue side
  *     @arg b6: the sentinel of blue side
  *     @arg b7: the drone of blue side
  * @retval None
  */
/respawn -r Bot

/**
  * @brief  Get help of this game.
  * @param  None.
  * @retval None
  */
/help
-------------------------------------------------------------------------------------------------------END-------------------------------------------------------------------------------------------------
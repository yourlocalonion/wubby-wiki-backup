> If `[player]` is omitted, it will default to the player that ran the command
{.is-info}


# <i class="fa-duotone fa-user"></i> Visitor+
| Command | Description |
|-----|---------|
| cmds | Opens a command list |
| rejoin | Rejoins whoever ran this command |
| notepad | Opens a GUI that allows you to write anything in it. |

# <i class="fa-duotone fa-user-helmet-safety"></i> Builder+
| Command | Arguments | Description |
|-----|---------|-------------|
| blind | `[player]` | Makes `[player]` unable to see |
| blur | `[player]` `(size)` | Blurs `[player]`'s screen by `(size)` amount |
| bring | `[player]` | Teleports `[player]` to whoever ran this command |
| burn | `[player]` `(damage)` `(showEffect)` | Sets `[player]` on fire, taking `(damage)` every second. Setting `(showEffect)` to false makes the fire invisible |
| cameraoffset | `[player]` `[offset]` | Offsets `[player]`'s camera to `[offset]` |
| camerashake | `[player]` `[time]` `[force]` | Shakes `[player]`'s camera for [time] seconds with a force of  [force]
| clip | `[player]` | Stops `[player]` from walking through walls |
| damage/dmg | `[player]` `(amount)` | Decreases `[player]`'s health by `(amount)` |
| disablefreecam | `[player]` | Disables freecam for `[player]` |
| explode/exp | `[player]` | Explodes `[player]`, the explosion might move nearby objects |
| fix/removeeffects | `[player]` | Removes every single effect applied to `[player]` (blur, fov, blindness, etc.) |
| fling | `[player]` `(amount)` | Flings `[player]` at a speed of `(amount)` |
| fly | `[player]` | Makes `[player]` fly |
| flyspeed | `[player]` `(amount)` | Sets `[player]`'s flying speed to `(amount)` |
| fov/fieldofview | `[player]` `(fov)` | Sets `[player]`'s field of view to `(fov)` |
| freecamstiff | `[player]` `[velStiff]` `[panStiff]` | Sets [player]'s freecam velocity stiffness to `[velstiff]` and its pan stiffness to `[panstiff]` |
| freeze/anchor | `[player]` | Freezes `[player]`, `[player]` wont be able to move |
| ghost/gh | `[player]` | Turns `[player]` into a ghost |
| god | `[player]` | Makes `[player]` invincible from all damage (unless killed) |
| gyro | `[player]` | Prevents `[player]` from changing orientation |
| heal | `[player]` `(amount)` | Increases `[player]`'s health by `(amount)` OR sets it to the `[player]`'s maxhealth if `(amount)` is not specified |
| highlight | `[player]` `(brickcolor)` | Makes `[player]` visible through walls with the color `(brickcolor)` |
| invisible/inv/invis/hide | `[player]` `(isVisible)` | Makes `[player]` invisible, if `(isVisible)` is "false", the player won't be able to see themselves |
| jump | `[player]` | Forces `[player]` to jump |
| jumppower | `[player]` `(amount)` | Changes `[player]`'s jumppower to `(amount)` |
| kill/die | `[player]` | Kills `[player]` |
| lightning/smite/thunder | `[player]` | Summons Zeus and throws a lightning bolt at `[player]` |
| magnet | `[player]` `(amount)` | Attracts every single player to `[player]` with a force of `(amount)` |
| maxhealth | `[player]` `(amount)` | Sets `[player]`'s maximum health to `(amount)` |
| message/m/msg/shout/announce | `[player]` (message) | Displays (message) in `[player]`'s screen |
| noclip | `[player]` | Allows `[player]` to walk through walls. |
| mute | `[player]` | Disables `[player]`'s ability to talk, Only works for permissions below you. (Builder cannot mute Admins+)
| nuke | `[player]`/`[coordinates]` | Places a nuke in `[player]`/`[coordinates]` |
| removelimbs | `[player]` | Removes `[player]`'s limbs |
| respawn | `[player]` | Respawns `[player]`, Basically removes the `[player]`'s character and places it where it was |
| sit/trip | `[player]` | Forces `[player]` to sit |
| sparkles/sparkle | `[player]` `(color)` | Gives `[player]` some sparkles with the color `(color)` |
| team name/teams name | `[teamName]` `[newName]` | Changes `[teamName]`'s name to `[newName]` |
| team set/teams set | `[player]` `[teamName]` | Sets `[player]`'s team to `[teamName]` |
| time | `[time]` | Sets the world time to `[time]` |
| to/tp/teleport | ``(player)`` `(player2)`/`(coordinates)` | If no parameters are entered, this command will teleport whoever ran this command to their mouse position. If ``(player)`` is entered, this command will teleport whoever ran this command to ``(player)``. If ``(player)`` and `(player2)` are entered, this command will teleport ``(player)`` to `(player2)`. If `(coordinates)` are entered, this command will teleport whoever ran this command to `(coordinates)`. |
| trail | `[player]` `(color)` | Puts a trail in `[player]`, its color will be `(color)` |
| unblind | `[player]` | Makes `[player]` able to see again |
| unblur | `[player]` | Unblurs `[player]`'s screen |
| unfly | `[player]` | Removes `[player]`'s ability to fly |
| unfreeze/thaw/unanchor | `[player]` | Unfreezes `[player]` |
| ungod | `[player]` | Makes `[player]` vulnerable to damage |
| ungyro | `[player]` | Allows `[player]` to change orientation again |
| unhighlight | `[player]` | Removes `[player]`'s highlight |
| unmagnet | `[player]` | Removes `[player]`'s magnet |
| unmute | `[player]` | Allows `[player]` to talk again. |
| visible/vis | `[player]` | Makes `[player]` visible again |
| walkspeed | `[player]` `(amount)` | Changes `[player]`'s walkspeed to `(amount)` |

# <i class="fa-duotone fa-user-police-tie"></i> Admin+
| Command | Arguments | Description |
|-----|---------|-------------|
| ban | `[player]` | Prevents `[player]` from joining the game |
| kick | `[player]` `(reason)` | Kicks `[player]` with the reason `(reason)` |
| stat/stats add | `[statName]` | Creates a new stat with the name `[statName]` |
| stat/stats name | `[statName]` `[newName]` | Changes `[statName]`'s name to `[newName]` |
| stat/stats remove | `[statName]` | Removes the stat under the name `[statName]` |
| stat/stats set | `[statName]` `[player]` `(value)` | Sets `[player]`'s `[statName]` value to `(value)` |
| stat/stats visible | `[statName]` `(isVisible)` | Toggles the visibility of `[statName]`, if `(isVisible)` is "false", `[statName]` will not be shown on the playerlist |
| team/teams add | `[teamName]` `(teamColor)` | Creates a new team with the name `[teamName]` and the color `(teamColor)`. If `(teamColor)` is not specified, the team will be created with a random color |
| team/teams autoassign | `[teamName]` `(isEnabled)` | Sets if new players should be automatically assigned to `[teamName]` or not. If there are multiple teams with this setting enabled, the player will be assigned to the team with the least players |
| team/teams color | `[teamName]` `[teamColor]` | Changes `[teamName]`'s color to `(teamColor)` |
| team/teams remove | `[teamName]` | Removes the team under the name `[teamName]` |
| unban | `[player]` | Allows `[player]` to join the game |

# <i class="fa-solid fa-user-crown"></i> Creator+
| Command | Arguments | Description |
|-----|---------|-------------|
| clearduplicates | - | Clears every block that has the same size, rotation and position as another block |

# <i class="fa-duotone fa-user-secret"></i> Staff+
| Command | Arguments | Description |
|-----|---------|-------------|
| globalban | `[player]` `[reason]` | Permanently bans `[player]` from wubby with `[reason]` |
| globaltempban | `[player]` `[duration]` `[reason]` | Temporarily bans `[player]` from wubby for `[duration]` days with `[reason]` |
| globalunban | `[player]` | Unbans `[player]` from wubby |
| putonreview | - | Puts a world under review until ger approves it |
| feature | - | Toggles if a world will appear on the featured tab or not |
| clearworlddata | - | Clears all information about a world. |
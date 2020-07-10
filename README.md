# death_timer
Players are forced to wait an amount of time on re-spawn. 

On death players are cloaked and their interact privilege is removed. 

Players are held in place by a entity.

# Additional note
Fork by Mathias for a bug fix as Coder12's release has the respawn delay broken after the player respawns after the second death. Since this mod is more functional it would be a better appropriate candidate for release on ContentDB.

Optimized for 5.0.0, 5.0.1, 5.1.0, 5.1.1, 5.2.0, 5.3.0.

# config

The initial timeout on respawn.

``` lua
death_timer.initial_timeout = 8
```

The extra timeout values to add after the initial timeout (disable this by setting it to zero)

``` lua
death_timer.timeout = 1
```

The time it takes to reduce the death timeout (disable this by setting it to zero)

``` lua
death_timer.timeout_reduce_loop = 3600
```

The amount to reduce from the death timer timeout (disable this by setting it to zero)

``` lua
death_timer.timeout_reduce_rate = 1
```

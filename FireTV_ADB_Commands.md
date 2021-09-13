#Send Event Command to pause and resume playback. Note copy and past the below into the action -> command section of your automation.  No quote marks.

sendevent /dev/input/event4 4 4 786637 && sendevent /dev/input/event4 1 164 1 && sendevent /dev/input/event4 0 0 0 && sendevent /dev/input/event4 4 4 786637 && sendevent /dev/input/event4 1 164 0 && sendevent /dev/input/event4 0 0 0
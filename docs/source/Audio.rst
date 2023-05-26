
Audio Module
------------

This module provides functions for working with audio-related operations.

Functions
---------

.. function:: Audio.loadSound(filename)

   Loads a sound from the specified file.

   :param str filename: The filename of the sound.

.. function:: Audio.unloadSound(filePath)

   Unloads the sound specified by the file path.

   :param str filePath: The file path of the sound to unload.

.. function:: Audio.isVoiceValid(voiceID)

   Checks if the specified voice ID is valid.

   :param int voiceID: The voice ID to check.

.. function:: Audio.onVoiceEndFreeSoundEffect(voiceID, loopTimeStretchEffect)

   Frees the sound effect associated with the voice when it ends.

   :param int voiceID: The voice ID.
   :param bool loopTimeStretchEffect: Indicates whether the voice is looping with time stretch effect.

.. function:: Audio.onVoiceEndFreeEffectChain(voiceID, loopTimeStretchChain)

   Frees the effect chain associated with the voice when it ends.

   :param int voiceID: The voice ID.
   :param bool loopTimeStretchChain: Indicates whether the voice is looping with time stretch chain.

.. function:: Audio.createEffectChain(chainName)

   Creates a new effect chain with the specified name.

   :param str chainName: The name of the effect chain.

.. function:: Audio.getSoundLength(filename)

   Returns the length of the sound file in seconds.

   :param str filename: The filename of the sound.

.. function:: Audio.setVoiceGateTime(voiceID, gateTime)

   Sets the gate time for the voice with the specified ID.

   :param int voiceID: The voice ID.
   :param float gateTime: The gate time value.

.. function:: Audio.playSound(filename, C4, gateTime, priority, loopTimeStretchChain, position)

   Plays the sound specified by the file name.

   :param str filename: The filename of the sound.
   :param float C4: The C4 value.
   :param float gateTime: The gate time value.
   :param int priority: The priority value.
   :param int loopTimeStretchChain: The loop time stretch chain.
   :param int position: The position value.

.. function:: Audio.setVoiceSpeed(voiceID, speed)

   Sets the speed of the voice with the specified ID.

   :param int voiceID: The voice ID.
   :param float speed: The speed value.

.. function:: Audio.setVoicePosition(voiceID, position)

   Sets the position of the voice with the specified ID.

   :param int voiceID: The voice ID.
   :param int position: The position value.

.. function:: Audio.setVoiceLoopCount(voiceID, count)

   Sets the loop count for the voice with the specified ID.

   :param int voiceID: The voice ID.
   :param int count: The loop count value.

.. function:: Audio.spawnSoundSlicker(filename, gateTime, noteOfsFromC4, timeFactor, position)

   Spawns a sound slicker with the specified parameters.

   :param str filename: The filename of the sound.
   :param float gateTime: The gate time value.
   :param float noteOfsFromC4: The note offset from C4.
   :param float timeFactor: The time factor value.
   :param int position: The position value.

.. function:: Audio.setVoiceVolume(voiceID, volume)

   Sets the volume of the voice with the specified ID.

   :param int voiceID: The voice ID.
   :param float volume: The volume value.

.. function:: Audio.setVoiceLoop(voiceID, enable)

   Enables or disables looping for the voice with the specified ID.

   :param int voiceID: The voice ID.
   :param bool enable: Indicates whether looping is enabled.

.. function:: Audio.setVoicePause(voiceID, pause)

   Pauses or resumes the voice with the specified ID.

   :param int voiceID: The voice ID.
   :param bool pause: Indicates whether to pause or resume the voice.

.. function:: Audio.loadScriptFromFile(filePath, area)

   Loads a script from the specified file path.

   :param str filePath: The file path of the script.
   :param str area: The area where the script file is located.

.. function:: Audio.startPlayingScript()

   Starts playing the loaded script.

.. function:: Audio.isPlayingScript()

   Checks if the script is currently playing.

.. function:: Audio.stopPlayingScript()

   Stops playing the script.

.. function:: Audio.fadeOutVoice(voiceID, milliseconds)

   Fades out the voice with the specified ID over the specified duration.

   :param int voiceID: The voice ID.
   :param int milliseconds: The duration of the fade out in milliseconds.

.. function:: Audio.hack_setEnabled(enable)

   Enables or disables audio. (Unknown purpose)

   :param int enable: Indicates whether audio is enabled or disabled.

.. function:: Audio.setMasterVolume(volume)

   Sets the master volume for all audio.

   :param float volume: The volume value.

.. function:: Audio.unloadAllSounds()

   Unloads all loaded sounds.

.. function:: Audio.stopAllVoices()

   Stops all currently playing voices.

.. function:: Audio.startRecordingScript()

   Starts recording the audio script.

.. function:: Audio.isRecordingScript()

   Checks if the audio script is currently being recorded.

.. function:: Audio.isRecording()

   Checks if audio is currently being recorded.

.. function:: Audio.stopRecording()

   Stops the audio recording.

.. function:: Audio.stopRecordingScript()

   Stops the audio script recording.

.. function:: Audio.isVoiceValid(voiceID)

   Checks if the specified voice ID is valid.

   :param int voiceID: The voice ID.

.. function:: Audio.getMasterVolume()

   Returns the master volume value.

.. function:: Audio.setVoiceSpeed(voiceID, speed)

   Sets the speed of the voice with the specified ID.

   :param int voiceID: The voice ID.
   :param float speed: The speed value.

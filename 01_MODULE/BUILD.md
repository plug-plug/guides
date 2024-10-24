### materials needed
1. **microphone capsule**: replace the existing one or build from parts. use a high-sensitivity, noise-canceling type.
2. **wiring**: fine copper wires for connecting the microphone to the plug circuitry.
3. **soldering tools**: soldering iron, solder, and flux.
4. **outer casing**: to protect the microphone; consider using plastic or metal casing.
5. **SOUND_GEN_MODEL.pkl**: the AI model file for sound processing.
6. **tools**:
   - soldering iron.
   - small flathead screwdriver.
   - tweezers.
   - vice (optional).

![MIC_MODULE](https://github.com/plug-plug/unmute/02_ARTIFACTS/MISC/MIC_MODULE.png?raw=true)

### assembly steps
1. **remove old microphone**
   - carefully open the plug device using a small flathead screwdriver. identify the existing microphone capsule and use a soldering iron to disconnect it from the circuitry.

2. **install new microphone**
   - position the new **microphone capsule** where the old one was located. solder the **fine copper wires** to connect the microphone to the plug's circuit board. ensure the connections are secure and insulated to avoid short circuits.

3. **install the AI model**
   - connect the plug device to your computer.
   - load the **SOUND_GEN_MODEL.pkl** file onto the device using the provided software interface. this model will handle sound processing for the new microphone.

4. **reassemble the plug**
   - once the new microphone is installed and the AI model is loaded, carefully place the **outer casing** back onto the plug device. use a vice or rig if needed to ensure everything fits snugly.

### troubleshooting tips
- **no sound output**: check the soldering points for the microphone wires. ensure they are properly connected and there are no cold joints.
- **poor sound quality**: verify that the **SOUND_GEN_MODEL.pkl** file is correctly loaded and the microphone capsule is positioned correctly.
- **device not recognized**: if the device isn't recognized by your computer, try using a different USB cable or port.

### maintenance
- regularly inspect the **microphone capsule** for dust or damage. clean carefully to maintain optimal sound quality.
- ensure the **wiring** remains secure and free from corrosion.


![g](https://hcpp20334.github.io/Pictures/20240725_203430.png)
# UNIT API

```JAVASCRIPT
let fGUI = new GUI_FUNC();
```
# UNIT API MEM API
```JAVASCRIPT
//memory api
let fMem = new memory_api();
```
# FUNCTIONS PWEngine
```JAVASCRIPT
RTaudioInfo(audio_id,state)
pw_createAudio(injectID,setID)
pw_createWindow(injectID,setID,style);
pw_createText(injectID,setID,style)
pw_createButton(injectID,setID,style)
pw_createTag(injectID,setID,tagtype,style)
pw_destroyTag(getID)
pw_uninjectTag(getID,injectID)
pw_parseSlider(inputID)
```
# FUNCTION MEM API
```JAVASCRIPT
AddMem(mem_mb,obj_id) // dedicated memory obj,tag'su
```
# LOCAL PARAMS MEM API
```JAVASCRIPT
mem_usage;// js memory used heap size
mem_heap;// js heap size memory limit
mem_buffer;// js memory total memory size
```
# LOCAL PARAMS PWEngine
```JAVASCRIPT
build;// get build 
pw // analog document;
hwnd // analog window;
```

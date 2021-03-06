# Sipeed
Información relacionada con el desarrollo de las placas Maix
# References
- Sipeed Blog: https://blog.sipeed.com/p/1338.html
- Modelos creados por tereceros que pueden bajarse: https://www.maixhub.com/
- Recursos desarrolladores: https://wiki.sipeed.com/
- Github: https://github.com/sipeed/ 
- Instrucciones para nuevo aprendizaje y obtener nuevos modelos desde su web: https://www.maixhub.com/index/mtrain/help.html
- MaixPy documentation: https://maixpy.sipeed.com/en/
- Mobilenets abstract: https://arxiv.org/pdf/1704.04861.pdf
- Foro: https://en.bbs.sipeed.com/top/yearly
TUTORIALS
- Tutorial: Run Yolo2 on Sipeed Maix Bit :https://courses.cs.washington.edu/courses/cse475/19au/labs/yolo2_tutorial.html
- Image Recognition With K210 Boards and Arduino IDE/Micropython: https://www.instructables.com/id/Transfer-Learning-With-Sipeed-MaiX-and-Arduino-IDE/

# Entornos de trabajo IDE
- MaixPy documentation: https://maixpy.sipeed.com/en/
- Micropyhton: http://docs.micropython.org/en/latest/reference/index.html
# Ejemplos
- Scripts de ejemplo para MaixPY https://github.com/sipeed/MaixPy_scripts
- https://courses.cs.washington.edu/courses/cse475/19au/labs/yolo2_tutorial.html
- Re-Learns: https://www.instructables.com/id/Transfer-Learning-With-Sipeed-MaiX-and-Arduino-IDE/

Material y ejemplos Maixduino
- http://acoptex.com/project/9956/basics-project-083d-sipeed-maixduino-kit-for-risc-v-ai-and-iot-at-acoptexcom/#sthash.oauYEKNW.dpbs

Configuración inicial (https://maixpy.sipeed.com/en/get_started/get_hardware.html
- Instalar Driver -> Instalar drivers USB https://www.ftdichip.com/Drivers/D2XX.htm  (Available as a setup executable)
- Instalación ultima firmaware MaixPY: https://dl.sipeed.com/MAIX/MaixPy/release/master/maixpy_v0.5.0_221_g6460c58 
- Flashear el modelo en la direccion 0300000 -> lo hace automaticamente desde Kflash y no interfiere con el firmaware
- Cargar en MaixPY el script y subirlo. -> 
- Para bajarse modelos de ejemplo de https://www.maixhub.com/. previamente deberá flashearse un fichero bin que se obtiene de la misma web para obtener la Key de la placa que luego se entra en la web y de esta forma se activa el download del ejemplo
Debería funcionar 

ENTRENAMIENTO
- https://en.bbs.sipeed.com/t/topic/682

Otros Recursos
- From Google (anaconda): https://colab.research.google.com/drive/1VcSTUc8ws6az5sV_e_kGdP7fNs2QKg_t
- https://colab.research.google.com/github/AIWintermuteAI/aXeleRate/blob/master/resources/aXeleRate_pascal20_detector.ipynb?authuser=1

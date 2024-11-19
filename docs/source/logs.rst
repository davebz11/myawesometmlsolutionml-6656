Latest Logs From Latest Build
==============================

Generated On: 2024-11-19 23:06:24 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/davebz11/raspberrypi/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2024-11-19_23:03:05] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2024-11-19_23:03:09] STEP 2: Create topics started

  [INFO 2024-11-19_23:03:26] STEP 2: Completed

  [INFO 2024-11-19_23:03:33] STEP 3: producing data started

  [ERROR 2024-11-19_23:03:36] Cannot connect to MQTT broker in tml_read_MQTT_step_3_kafka_producetotopic_dag-myawesometmlsolutionml-6656.py - invalid literal for int() with base 10: ''

  [INFO 2024-11-19_23:03:36] STEP 4: Preprocessing started

  [INFO 2024-11-19_23:03:40] STEP 7: Visualization started

  [INFO 2024-11-19_23:03:42] STEP 4: Preprocessing started

  [INFO 2024-11-19_23:03:52] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 9005

  [INFO 2024-11-19_23:03:59] STEP 8: Starting docker push for: marley88/myawesometmlsolutionml-6656-amd64

  [INFO 2024-11-19_23:04:25] STEP 8: Docker Container created.  Will push it now.  Here is the commit command: docker commit abb4e07035ef marley88/myawesometmlsolutionml-6656-amd64 - message=0

  [INFO 2024-11-19_23:06:15] STEP 8: Successfully ran Docker push: docker push marley88/myawesometmlsolutionml-6656-amd64 - message=0

  [ERROR 2024-11-19_23:06:15] STEP 8: Deploying to Docker in tml_system_step_8_deploy_solution_to_docker_dag-myawesometmlsolutionml-6656.py: [Errno 2] No such file or directory: '/raspberrypi/tml-airflow/dags/tml-solutions/myawesometmlsolutionml-6656/docker_run_stop-myawesometmlsolutionml-6656.py'

  [INFO 2024-11-19_23:06:24] STEP 10: Started to build the documentation

  [INFO 2024-11-19_23:06:24] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds



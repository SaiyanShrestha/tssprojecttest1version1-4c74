Latest Logs From Latest Build
==============================

Generated On: 2024-12-02 13:05:21 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/saiyanshrestha/raspberrypi/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2024-12-02_13:02:59] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2024-12-02_13:03:04] STEP 2: Create topics started

  [INFO 2024-12-02_13:03:24] STEP 2: Completed

  [INFO 2024-12-02_13:03:35] STEP 3: producing data started

  [INFO 2024-12-02_13:03:39] MQTT connection established...

  [INFO 2024-12-02_13:03:40] STEP 4: Preprocessing started

  [INFO 2024-12-02_13:03:43] STEP 4: Preprocessing started

  [INFO 2024-12-02_13:03:45] STEP 7: Visualization started

  [INFO 2024-12-02_13:03:52] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 9005

  [INFO 2024-12-02_13:04:01] STEP 9: Starting privateGPT

  [INFO 2024-12-02_13:04:11] STEP 8: Starting docker push for: saiyanshrestha/tssprojecttest1version1-4c74-amd64

  [INFO 2024-12-02_13:04:18] STEP 9: Success starting privateGPT.  Here is the run command: docker run -d -p 8001:8001 --net=host --env PORT=8001 --env GPU=0 --env COLLECTION=tml --env WEB_CONCURRENCY=1 --env CUDA_VISIBLE_DEVICES=0 maadsdocker/tml-privategpt-no-gpu-amd64

  [INFO 2024-12-02_13:04:38] STEP 8: Docker Container created.  Will push it now.  Here is the commit command: docker commit 3df99636698e saiyanshrestha/tssprojecttest1version1-4c74-amd64 - message=0

  [WARN 2024-12-02_13:04:58] STEP 8: There may be an issue pushing to Docker Hub, or just wait few seconds to see if the container shows up.  Here is the command: docker push saiyanshrestha/tssprojecttest1version1-4c74-amd64 - message=1

  [INFO 2024-12-02_13:05:20] STEP 10: Started to build the documentation

  [INFO 2024-12-02_13:05:22] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds



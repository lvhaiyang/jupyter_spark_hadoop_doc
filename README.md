# jupyter_spark_hadoop_doc
images wuchenlhy/jupyter_spark_hadoop instructions

In the jupyterLab + PySpark + Spark + Hadoop environment, ports jupyterLab 8888 and spark 8080 need to be mapped

Create container command

docker run -itd \
    --name jupyter_spark_hadoop \
    -p 8888:8888 \
    -p 8080:8080 \
    -v ${The path to be mounted}:/root/data/  \
    wuchenlhy/jupyter_spark_hadoop:2.0
    
jupyterlab url
http://ip:8888
<img width="812" alt="image" src="https://user-images.githubusercontent.com/29853564/153972709-eabc4137-a9be-4f1d-8904-4690b9cfff23.png">

spark url
http://ip:8080
<img width="1439" alt="image" src="https://user-images.githubusercontent.com/29853564/153972762-ca318b77-9631-4279-b587-25ae1dfeb853.png">

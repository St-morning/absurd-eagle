#!/bin/bash
ip="10.151.1.24"
port="4417"
username="ceshi"
password="Vcom@123456"
echo '-------------- 导出 sch_student 表到hive ------------------------------'
sudo -u hdfs sqoop import \
--connect "jdbc:mysql://${ip}:${port}/ucs?useUnicode=true&characterEncoding=utf-8" \
--username "${username}" \
--password  ${password} \
--driver com.mysql.jdbc.Driver \
--null-string '\\N' \
--null-non-string '\\N' \
-m 1 \
--hive-import \
--hive-overwrite \
--table sch_student \
--hive-table ods.sch_student
echo '-------------- 导出 cfg_area 表到hive ------------------------------'
sudo -u hdfs sqoop import \
--connect "jdbc:mysql://${ip}:${port}/ucs?useUnicode=true&characterEncoding=utf-8" \
--username "${username}" \
--password  ${password} \
--driver com.mysql.jdbc.Driver \
--null-string '\\N' \
--null-non-string '\\N' \
-m 1 \
--hive-import \
--hive-overwrite \
--table cfg_area \
--hive-table ods.cfg_area

echo '-------------- 导出 sch_school 表到hive ------------------------------'
sudo -u hdfs sqoop import \
--connect "jdbc:mysql://${ip}:${port}/ucs?useUnicode=true&characterEncoding=utf-8" \
--username "${username}" \
--password  ${password} \
--driver com.mysql.jdbc.Driver \
--null-string '\\N' \
--null-non-string '\\N' \
-m 1 \
--hive-import \
--hive-overwrite \
--table sch_school \
--hive-table ods.sch_school

echo '-------------- 导出 edu_grade 表到hive ------------------------------'
sudo -u hdfs sqoop import \
--connect "jdbc:mysql://${ip}:${port}/ucs?useUnicode=true&characterEncoding=utf-8" \
--username "${username}" \
--password  ${password} \
--driver com.mysql.jdbc.Driver \
--null-string '\\N' \
--null-non-string '\\N' \
-m 1 \
--hive-import \
--hive-overwrite \
--table edu_grade \
--hive-table ods.edu_grade

echo '-------------- 导出 sch_class 表到hive ------------------------------'
sudo -u hdfs sqoop import \
--connect "jdbc:mysql://${ip}:${port}/ucs?useUnicode=true&characterEncoding=utf-8" \
--username "${username}" \
--password  ${password} \
--driver com.mysql.jdbc.Driver \
--null-string '\\N' \
--null-non-string '\\N' \
-m 1 \
--hive-import \
--hive-overwrite \
--table sch_class \
--hive-table ods.sch_class
echo '-------------- 导出 t_urc_catalogue 表到hive ------------------------------'
sudo -u hdfs sqoop import \
--connect "jdbc:mysql://${ip}:${port}/nrms?useUnicode=true&characterEncoding=utf-8" \
--username "${username}" \
--password  ${password} \
--driver com.mysql.jdbc.Driver \
--null-string '\\N' \
--null-non-string '\\N' \
-m 1 \
--hive-import \
--hive-overwrite \
--table t_urc_catalogue \
--hive-table ods.t_urc_catalogue
echo '-------------- 导出 t_urc_item_label 表到hive ------------------------------'
sudo -u hdfs sqoop import \
--connect "jdbc:mysql://${ip}:${port}/nrms?useUnicode=true&characterEncoding=utf-8" \
--username "${username}" \
--password  ${password} \
--driver com.mysql.jdbc.Driver \
--null-string '\\N' \
--null-non-string '\\N' \
-m 1 \
--hive-import \
--hive-overwrite \
--table t_urc_item_label \
--hive-table ods.t_urc_item_label

echo '-------------- 导出 t_protal_platform 表到hive ------------------------------'
sudo -u hdfs sqoop import \
--connect "jdbc:mysql://${ip}:${port}/protal?useUnicode=true&characterEncoding=utf-8" \
--username "${username}" \
--password  ${password} \
--driver com.mysql.jdbc.Driver \
--null-string '\\N' \
--null-non-string '\\N' \
-m 1 \
--hive-import \
--hive-overwrite \
--table t_protal_platform \
--hive-table ods.t_protal_platform

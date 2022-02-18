### 关于代理无法转换Json

- 在类前添加注释，忽略“handler”：

  ```java
  @JsonIgnoreProperties(value = "handler")
  ```

- 时间格式的转换

  ```java
  根据类型设置：   
  	@JsonFormat(timezone = "GMT+8", pattern = "HH:mm:ss")
      @JsonFormat(timezone = "GMT+8", pattern = "yyyy-MM-dd")
      @JsonFormat(timezone = "GMT+8", pattern = "yyyy-MM-dd HH:mm:ss")
  ```

  ![VXHQ2}}SGTC$ TFIU27M{GE](https://user-images.githubusercontent.com/70928257/154637138-394806a1-9034-4ed9-963d-3fe631cdcc47.png)



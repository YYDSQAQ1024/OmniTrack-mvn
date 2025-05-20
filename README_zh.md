# OmniTrack Meven repositories
使用下方代码导入依赖
```
  <repositories>
      <repository>
          <id>maven-repository</id>
          <url>https://raw.github.com/YYDSQAQ1024/OmniTrack-mvn/main</url>
          <snapshots>
              <enabled>true</enabled>
              <updatePolicy>always</updatePolicy>
          </snapshots>
      </repository>
  </repositories>

  <dependencies>
      <dependency>
          <groupId>me.wang</groupId>
          <artifactId>OmniTrack</artifactId>
          <version>1.0</version><!--Replace with the latest version-->
          <scope>provided</scope>
      </dependency>
  </dependencies>
```
获取OmniTrack API:
```
import me.wang.omnitrack.OmniTrack;
import me.wang.omnitrack.api.OmniTrackAPI;
...
OmniTrack omniTrack = (OmniTrack) getServer().getPluginManager().getPlugin("OmniTrack");
OmniTrackAPI api = omniTrack.getAPI();
```

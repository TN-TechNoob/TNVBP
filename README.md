![TNVBP](https://i.imgur.com/TTzZoVa.png)
![Modrinth Downloads](https://img.shields.io/modrinth/dt/Ohwb2cTF?label=Downloads&logo=modrinth&style=flat-square)
![Modrinth Game Versions](https://img.shields.io/modrinth/game-versions/Ohwb2cTF?logo=modrinth&style=flat-square)
[![Discord](https://img.shields.io/discord/607123183249653770?label=Discord&logo=discord&style=flat-square)](https://discord.gg/Yj9WH3P8RN)

<h3>關於模組包</h3>
<ul>
    <li>基於 <a href="https://modrinth.com/mod/sodium">Sodium</a> 渲染引擎及其他優化模組來優化效能</li>
    <li>內含 <a href="https://modrinth.com/mod/iris">Iris</a> 光影模組，可以安裝<a href="https://modrinth.com/shaders?g=categories:%27iris%27">支援 Iris 的光影</a></li>
    <li>模組包自帶設定檔，使用者不喜歡也可以自己手動調整</li>
    <li>遊戲內各種特殊場景效能<a href="https://modrinth.com/modpack/tnvbp/gallery">截圖圖庫</a></li>
</ul>

<h3>TNVBP 版本差異</h3>
<ul>
    <li><a href="https://modrinth.com/modpack/tnvbp">TNVBP</a> 較適合安裝模組包後就直接遊玩的玩家</li>
    <li><a href="https://modrinth.com/modpack/tnvbp-lite">TNVBP Lite</a> 則比較適合拿來當作優化效能的基礎模組包，安裝模組包後再加上自己想要的模組</li>
    <table>
        <tr>
            <th></th>
            <th><a href="https://modrinth.com/modpack/tnvbp">TNVBP</a></th>
            <th><a href="https://modrinth.com/modpack/tnvbp-lite">TNVBP Lite</a></th>
        </tr>
        <tr>
            <th>版本支援</th>
            <th>1.18~1.21</th>
            <th>1.18~1.21</th>
        </tr>
        <tr>
            <th>核心模組</th>
            <th><a href="https://modrinth.com/mod/sodium">Sodium</a></th>
            <th><a href="https://modrinth.com/mod/sodium">Sodium</a></th>
        </tr>
        <tr>
            <th>界伏盒預覽</th>
            <th>✅</th>
            <th>❌</th>
        </tr>
        <tr>
            <th>遊戲內數據收集</th>
            <th>✅</th>
            <th>❌</th>
        </tr>
        <tr>
            <th>遊戲內帳號切換</th>
            <th>✅</th>
            <th>❌</th>
        </tr>
        <tr>
            <th>其他 QOL 模組</th>
            <th>✅</th>
            <th>❌</th>
        </tr>
    </table>
</ul>

<h3>Java 下載及設定</h3>
<ul>
    <p>Minecraft 1.20.6 以下版本其實也可以使用 Java 21 執行，只要勾選 <code>略過 Java 相容性檢查</code> 即可</p>
    <table>
        <tr>
            <th colspan="7">Java 21 下載</th>
        </tr>
        <tr>
            <th rowspan="2"><a href="https://adoptium.net/">Adoptium</a></th>
            <th colspan="2">Windows</th>
            <th colspan="2">Linux</th>
            <th colspan="2">macOS</th>
        </tr>
        <tr>
            <th><a href="https://adoptium.net/temurin/releases/?variant=openjdk21&jvmVariant=hotspot&package=jre&os=windows&arch=x64">x64</a></th>
            <th><a href="https://adoptium.net/temurin/releases/?variant=openjdk21&jvmVariant=hotspot&package=jre&os=windows&arch=aarch64">aarch64</a></th>
            <th><a href="https://adoptium.net/temurin/releases/?variant=openjdk21&jvmVariant=hotspot&package=jre&os=linux&arch=x64">x64</a></th>
            <th><a href="https://adoptium.net/temurin/releases/?variant=openjdk21&jvmVariant=hotspot&package=jre&os=linux&arch=aarch64">aarch64</a></th>
            <th><a href="https://adoptium.net/temurin/releases/?variant=openjdk21&jvmVariant=hotspot&package=jre&os=mac&arch=x64">x64</a></th>
            <th><a href="https://adoptium.net/temurin/releases/?variant=openjdk21&jvmVariant=hotspot&package=jre&os=mac&arch=aarch64">aarch64</a></th>
        </tr>
        <tr>
            <th rowspan="2"><a href="https://www.graalvm.org/">GraalVM</a></th>
            <th colspan="2">Windows</th>
            <th colspan="2">Linux</th>
            <th colspan="2">macOS</th>
        </tr>
        <tr>
            <th colspan="2"><a href="https://download.oracle.com/graalvm/21/latest/graalvm-jdk-21_windows-x64_bin.zip">x64</a></th>
            <th><a href="https://download.oracle.com/graalvm/21/latest/graalvm-jdk-21_linux-x64_bin.tar.gz">x64</a></th>
            <th><a href="https://download.oracle.com/graalvm/21/latest/graalvm-jdk-21_linux-aarch64_bin.tar.gz">aarch64</a></th>
            <th><a href="https://download.oracle.com/graalvm/21/latest/graalvm-jdk-21_macos-x64_bin.tar.gz">x64</a></th>
            <th><a href="https://download.oracle.com/graalvm/21/latest/graalvm-jdk-21_macos-aarch64_bin.tar.gz">aarch64</a></th>
        </tr>
    </table>
    <table>
        <tr>
            <th colspan="2">記憶體設定</th>
        </tr>
        <tr>
            <th>最大記憶體使用量</th>
            <th>4096 MB</th>
        </tr>
        <tr>
            <th>最小記憶體使用量</th>
            <th>4096 MB</th>
        </tr>
    </table>
    <h4>JVM 參數</h4>
    <pre><code>-XX:+UseZGC -XX:+ZGenerational -XX:+DisableExplicitGC -XX:+AlwaysPreTouch -XX:+PerfDisableSharedMem -XX:+UseDynamicNumberOfGCThreads</code></pre>
</ul>

<h3>問題回報</h3>
<ul>
    <li>若對模組包有任何問題和建議歡迎私訊我Discord：tn_technoob</li>
    <li>或到我的 Discord 群 <a href="https://discord.gg/Yj9WH3P8RN">TNSU丨塔可努的太空烏托邦</a> 回報</li>
</ul>

<details>
    <summary>
        <img src="https://i.imgur.com/4XuDWHv.png" alt="English" width="18">
        English
    </summary>

<h3>About Modpack</h3>
<ul>
    <li>Based on <a href="https://modrinth.com/mod/sodium">Sodium</a> render engine and other optimization mods to optimize performance</li>
    <li>Include the <a href="https://modrinth.com/mod/iris">Iris shader mod</a>, so you can install <a href="https://modrinth.com/shaders?g=categories:%27iris%27">shaders that Iris support</a></li>
    <li>The modpack comes with its own configuration file, you can still adjust it manually if you want to</li>
    <li><a href="https://modrinth.com/modpack/tnvbp/gallery">In-game benchmark screenshots</a></li>
</ul>

<h3>TNVBP Version Differences</h3>
<ul>
    <li><a href="https://modrinth.com/modpack/tnvbp">TNVBP</a> is designed for those who just want to install the modpack and play</li>
    <li><a href="https://modrinth.com/modpack/tnvbp-lite">TNVBP Lite</a> is more suitable as a basic performance optimization modpack, so you can add your favourite mods on top of it</li>
    <table>
        <tr>
            <th></th>
            <th><a href="https://modrinth.com/modpack/tnvbp">TNVBP</a></th>
            <th><a href="https://modrinth.com/modpack/tnvbp-lite">TNVBP Lite</a></th>
        </tr>
        <tr>
            <th>Support Versions</th>
            <th>1.18~1.21</th>
            <th>1.18~1.21</th>
        </tr>
        <tr>
            <th>Core Mod</th>
            <th><a href="https://modrinth.com/mod/sodium">Sodium</a></th>
            <th><a href="https://modrinth.com/mod/sodium">Sodium</a></th>
        </tr>
        <tr>
            <th>Shulker Box Preview</th>
            <th>✅</th>
            <th>❌</th>
        </tr>
        <tr>
            <th>In-game Data collection</th>
            <th>✅</th>
            <th>❌</th>
        </tr>
        <tr>
            <th>In-game Account Switcher</th>
            <th>✅</th>
            <th>❌</th>
        </tr>
        <tr>
            <th>Other QOL Mods</th>
            <th>✅</th>
            <th>❌</th>
        </tr>
    </table>
</ul>

<h3>Java Download & Configuration</h3>
<ul>
    <p>Minecraft 1.20.6 and below can actually run with Java 21, just check the <code>Skip Java compatibility checks</code> check box</p>
    <table>
        <tr>
            <th colspan="7">Java 21 Download</th>
        </tr>
        <tr>
            <th rowspan="2"><a href="https://adoptium.net/">Adoptium</a></th>
            <th colspan="2">Windows</th>
            <th colspan="2">Linux</th>
            <th colspan="2">macOS</th>
        </tr>
        <tr>
            <th><a href="https://adoptium.net/temurin/releases/?variant=openjdk21&jvmVariant=hotspot&package=jre&os=windows&arch=x64">x64</a></th>
            <th><a href="https://adoptium.net/temurin/releases/?variant=openjdk21&jvmVariant=hotspot&package=jre&os=windows&arch=aarch64">aarch64</a></th>
            <th><a href="https://adoptium.net/temurin/releases/?variant=openjdk21&jvmVariant=hotspot&package=jre&os=linux&arch=x64">x64</a></th>
            <th><a href="https://adoptium.net/temurin/releases/?variant=openjdk21&jvmVariant=hotspot&package=jre&os=linux&arch=aarch64">aarch64</a></th>
            <th><a href="https://adoptium.net/temurin/releases/?variant=openjdk21&jvmVariant=hotspot&package=jre&os=mac&arch=x64">x64</a></th>
            <th><a href="https://adoptium.net/temurin/releases/?variant=openjdk21&jvmVariant=hotspot&package=jre&os=mac&arch=aarch64">aarch64</a></th>
        </tr>
        <tr>
            <th rowspan="2"><a href="https://www.graalvm.org/">GraalVM</a></th>
            <th colspan="2">Windows</th>
            <th colspan="2">Linux</th>
            <th colspan="2">macOS</th>
        </tr>
        <tr>
            <th colspan="2"><a href="https://download.oracle.com/graalvm/21/latest/graalvm-jdk-21_windows-x64_bin.zip">x64</a></th>
            <th><a href="https://download.oracle.com/graalvm/21/latest/graalvm-jdk-21_linux-x64_bin.tar.gz">x64</a></th>
            <th><a href="https://download.oracle.com/graalvm/21/latest/graalvm-jdk-21_linux-aarch64_bin.tar.gz">aarch64</a></th>
            <th><a href="https://download.oracle.com/graalvm/21/latest/graalvm-jdk-21_macos-x64_bin.tar.gz">x64</a></th>
            <th><a href="https://download.oracle.com/graalvm/21/latest/graalvm-jdk-21_macos-aarch64_bin.tar.gz">aarch64</a></th>
        </tr>
    </table>
    <table>
        <tr>
            <th colspan="2">Memory Settings</th>
        </tr>
        <tr>
            <th>Maximum</th>
            <th>4096 MB</th>
        </tr>
        <tr>
            <th>Minimum</th>
            <th>4096 MB</th>
        </tr>
    </table>
    <h4>JVM arguments</h4>
    <pre><code>-XX:+UseZGC -XX:+ZGenerational -XX:+DisableExplicitGC -XX:+AlwaysPreTouch -XX:+PerfDisableSharedMem -XX:+UseDynamicNumberOfGCThreads</code></pre>
</ul>

<h3>Issues Report</h3>
<ul>
    <li>If you have any questions or suggestions about modpack, please DM my Discord: tn_technoob</li>
    <li>Or report at my Discord group: <a href="https://discord.gg/Yj9WH3P8RN">TNSU丨TechNoob's Space Utopia</a></li>
</ul>

</details>

<h3>支持塔可努丨TechNoob (ECPay綠界科技)</h3>
<a href="https://p.ecpay.com.tw/5F5F547">
    <img src="https://i.imgur.com/CBlFm05.png" alt="贊助=w=">
</a>

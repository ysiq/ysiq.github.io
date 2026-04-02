---
layout: zdzb
title: 智能网关
---

<div class="product-hero">
    <h2>智能网关</h2>
    <p>智能家居系统的核心控制中心</p>
</div>

<div class="product-image">
    <img src="/zdzb/smart-home/img/网关.png" alt="智能网关">
</div>

<div class="product-features">
    <h3>产品特点</h3>
    <ul class="specs-list">
        <li><strong>传输稳定</strong>：采用LoRa无线通讯技术，信号传输稳定可靠，覆盖范围广</li>
        <li><strong>多接口支持</strong>：配备网口和LoRa通讯模块，支持多种设备连接</li>
        <li><strong>集中控制</strong>：统一管理所有智能设备，实现智能化联动</li>
        <li><strong>远程访问</strong>：通过手机APP随时随地控制家中设备</li>
        <li><strong>安全可靠</strong>：采用多重加密技术，保障数据安全</li>
    </ul>
</div>

<div class="product-usage">
    <h3>产品参数</h3>
    <table>
        <tr>
            <th>产品参数</th>
            <th>规格</th>
        </tr>
        <tr>
            <td>产品名称</td>
            <td>智能家居网关</td>
        </tr>
        <tr>
            <td>产品型号</td>
            <td>SZYJ-B03</td>
        </tr>
        <tr>
            <td>产品尺寸</td>
            <td>73×72×25mm</td>
        </tr>
        <tr>
            <td>产品净重</td>
            <td>68g</td>
        </tr>
        <tr>
            <td>电源输入</td>
            <td>5V/1A</td>
        </tr>
        <tr>
            <td>工作环境</td>
            <td>-5℃~50℃    0%~95%RH,无冷凝</td>
        </tr>
        <tr>
            <td>有线连接</td>
            <td>10Mbps 支持DHCP</td>
        </tr>
        <tr>
            <td>无线连接</td>
            <td>lora</td>
        </tr>
        <tr>
            <td>连接子设备数量</td>
            <td>64个</td>
        </tr>
    </table>
    
    <h3>网关连接网络</h3>
    <ol>
        <li>将type-c的电源线接入网关，网关的led灯开始闪烁，说明网关上电成功，可以使用5V/1A的适配器，不可以使用快充。</li>
        <li>用网线将网关与路由器连接，此时观察led灯的状态，可以判断网关是否连接网络成功。</li>
    </ol>
    
    <table>
        <tr>
            <th>序号</th>
            <th>功能</th>
            <th>闪烁</th>
            <th>常亮</th>
        </tr>
        <tr>
            <td>1</td>
            <td>网关连接路由器的状态</td>
            <td>正在连接路由器</td>
            <td>已经连接上路由器</td>
        </tr>
        <tr>
            <td>2</td>
            <td>网关连接服务器的状态</td>
            <td>正在连接服务器</td>
            <td>已经连接上服务器</td>
        </tr>
        <tr>
            <td>3</td>
            <td>网关与服务器的通讯状态</td>
            <td>有服务器的数据下发</td>
            <td>(无此状态)</td>
        </tr>
    </table>
    
    <p>正常已连接服务器的情况下：1、2号灯常亮，3号灯偶尔闪烁。</p>
    <p>注意：路由器需要支持并开启DHCP功能，一般家用路由器都支持并开启了DHCP，如遇到网关路由灯一直闪烁的时候，请检查此项配置。</p>
    
    <ol start="3">
        <li>通过尚住APP扫描设备外壳上的设备ID二维码添加设备，即可在APP中看到设备。</li>
    </ol>
    
    <h3>子设备入网配置</h3>
    <div class="product-image">
        <img src="/zdzb/smart-home/img/设备入网按键.png" alt="设备入网按键">
    </div>
    <ol>
        <li>短按网关的入网按键（如上图所示），网关进入入网状态，此时网关的指示灯会闪烁。</li>
        <li>操作子设备进入入网状态（不同设备的操作方式可能不同）：
            <ul>
                <li><strong>墙面开关</strong>：长按开关按键5秒，直到指示灯闪烁</li>
                <li><strong>智能窗帘</strong>：连续按动窗帘电机按键5次</li>
                <li><strong>移动插座</strong>：长按插座按键5秒，直到指示灯闪烁</li>
            </ul>
        </li>
        <li>等待子设备入网成功，此时子设备的指示灯会停止闪烁并保持常亮。</li>
        <li>在APP中查看设备是否成功添加。</li>
    </ol>
    <h3>注意事项</h3>
    <p><strong>注意：</strong></p>
    <ol>
        <li>当有多个设备需要入网时，需要按照步骤一个一个的入网，不能有两个设备同时处于入网态。</li>
        <li>子设备进入入网状态后，指示灯闪烁，会一直处于入网态，除非入网成功或再次长按多功能按键取消入网。网关按下入网按键后，只会在1秒内处于允许子设备入网状态。当有设备入网成功或1秒后，会恢复到正常工作状态。</li>
    </ol>
    
    <h3>子设备退网</h3>
    <p>当设备不再使用或更换网关时，需要把设备先退网，只需要长按多功能按键，此时指示灯慢速闪烁几秒，说明退网成功。</p>
</div>
# Android-PDA-广播扫描
 * 自定义扫描类 用于接收不同设备的扫码广播并分发结果
 * 使用方法：<br>
 * 1.复制ScanBaseActivity到您的任意项目中
 * 2.需要修改广播 Action 和 广播输出字符串，也可能是广播输出字节数组(这俩参数具体在PDA查看或者由PDA生产商提供)
 * 3.在界面中继承ScanBaseActivity，使用onScanResult接收扫描结果
 * public class MainActivity extends ScanBaseActivity {
 *     @Override
 *     public void onScanResult(String data) {
 *         // 这里直接处理扫描结果
 *         Log.d("MainActivity", "扫描结果: " + data);
 *     }
 *     }
 * <br>

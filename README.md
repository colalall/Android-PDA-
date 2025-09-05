# Android-PDA-广播扫描
Android PDA广播扫描
自定义扫描类 用于接收不同设备的扫码广播并分发结果
 * 使用方法：<br>
 * public class MainActivity extends ScanBaseActivity {
 *     @Override
 *     public void onScanResult(String data) {
 *         // 这里直接处理扫描结果
 *         Log.d("MainActivity", "扫描结果: " + data);
 *     }
 *     }
 * <br>

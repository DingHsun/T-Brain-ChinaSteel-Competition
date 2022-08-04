# T-Brain Machine Learning Competition
# 中鋼人工智慧挑戰賽字元辨識
https://tbrain.trendmicro.com.tw/Competitions/Details/17

中鋼50年來致力於鋼鐵產業，有舉足輕重的地位，為世界知名鋼鐵廠。隨著人工智慧科技在許多領域已超越人類智能，中鋼放眼下一個50年的發展，已定調「精緻鋼鐵」、「綠能產業」是我們經營發展的兩大主軸，透過「智能化」讓中鋼再精進升級，希冀保持領先的競爭力。為慶祝中鋼50周年，特別舉辦「人工智慧挑戰賽」，挑戰賽的主題與智能化鋼胚的管理有密切的相關。
本次參賽者要以人工智慧演算法，實現鋼胚上印刷或手寫序號的自動判別，將有助於問題源的返溯及品質的控管。參賽者除了要能辨識正常印刷之序號（含數字及英文字母），還得針對手寫序號、序號上下顛倒、重複印刷序號、或序號模糊等情況做有效的處理，以發展出適合實際產線運作的序號辨識系統。

總參賽隊伍：321隊

參賽隊伍名稱：皮卡丘萬歲

Public Leaderboard : 46/321

Private Leaderboard : 45/321


模型建置與訓練測試流程：\\
因每張影像中手寫序號位置並不一致，且僅有訓練集有標示序號位置之x,y座標，因此我們首先訓練一個判斷序號位置的model，幫助我們自動找出尚未標示的影像，結果上標示的模型通常能正確的標出序號的位置。

接著

# 対数階乗について

　gluemathの内部ルーチンで使用するインライン関数に、対数階乗がある。階乗は、通常 自然数に現れるものであるが、乗積であるため対数が好まれることが多い。  
　グルー言語コミッタ用にメンテナンス・ツールの提供を目的として、素因数分解したリストを作成しているが、面白いことに、対数として変数に現れる因子は、素数そのものである。  
　この変数の現れ方はC.F.ガウスの素数近似論を彷彿とさせる。メーリングリストでも話題となっており、そのためgluemathから分離し、別途、理論化する次第となった。  
　この研究により、分数イデアル環には素数が必ず関係しているというのが判った。整数環にはオイラー・リーマンのゼータ関数が、べき級数環にはガンマ関数が関係する。恐らく、他の環も関係する関数があるだろう。  

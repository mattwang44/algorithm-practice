1. �Ǹ��G           R05522625
2. �m�W�G           ���µ�
3. �ϥΤ��{���y���G C++ (c++17)
4. �ϥΤ��sĶ���G   GNU g++ 
5. �ɮ����Y�覡:    zip
6. �U�ɮ׻����G
    main.cpp:          �D�{��
    main_noGraph.cpp:  �D�{��(�L�@�ϥ\�઩��)
    makefile:          �۰ʤƫغc���O
    build:             ������
    out:               ����d�ҿ�J��test.in����X��
    out_5x5:           ����d�ҿ�J��test_5x5.in����X��
    out_7x7:           ����d�ҿ�J��test_7x7.in����X��
    test.in.jpg:       ����d�ҿ�J��test.in����X�@��
    test_5x5.in.jpg:   ����d�ҿ�J��test_5x5.in����X�@��
    test_7x7.in.jpg:   ����d�ҿ�J��test_7x7.in����X�@��

7. �sĶ�覡�����G
   �D�{���Gmain.cpp
     �Цb�D�{�����ؿ��U�A��Jmake���O�A�Y�i�����sĶ
     ( Makefile���w�� Optimize ���O�� -O3 )�A
     �Y�q���L�k���`�ϥ�GNU plot�A�h���make noGraph���O�A
     �sĶ���|�@�Ϥ�������

8. ����B�ϥΤ覡�����G
   �D�{���G
    �sĶ������A�b�ɮץؿ��U�|���ͤ@�� build ��������
    �����ɪ��R�O�榡���G

        ./built <input file name> <output file name>

    �Ҧp�G�n�H test.in ������T�@Bezier Curve�ñN�����I�y�п�X��
    test.out�ç@�ϡA�h�b�R�O���ܤU��J�G

        ./build test.in test.out

    �K�|�b�ؿ��U�۰ʥͦ�(1)�t�����I�y�Ъ��ɮ�test.out �M
                        (2)�P��J�ɦP�W��jpg�� (�Y�Hmake noGrpah�sĶ�h�L)

9. ���浲�G�����G
   �D�{���G
     �D�{�����浲����|�b console ��X�`����ɶ��A�p�G
     
         Time taken: 6.86s

   ��X�ɡG
     �C��]�t�����I��x, y�y�СA�H�s���("\t")�j�}

   �@�ϡG
     �]�t�H����ø�s��Control Point�s�u���Ŧ�ø�s��Bezier Curve

10. �@�P�Q�ת̻P�ѦҸ�ơG
   a. �����{���b�P �Ұ�U�Чf���@ �� �׽ҦP�ǧ��|�a �Q�׫᧹��
   
   b. Bezier Curves -- Denis Rizov
      https://denisrizov.com/2016/06/02/bezier-curves-unity-package-included/

   c. GNUplot���Y��(�Ӧ�Google Code Archive)
      https://code.google.com/archive/p/gnuplot-cpp/downloads

   d. Demos for gnuplot version 5.2
      http://gnuplot.sourceforge.net/demo_5.2/

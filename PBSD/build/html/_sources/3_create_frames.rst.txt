========================
Frame 생성
========================

Frame은 Midas Gen의 Active와 비슷한 역할을 합니다. 노드와 부재가 많은 경우, **Frame을 만들어서 필요한 노드와 부재만 Active하여 모델링이 가능합니다.**
그러나 Midas Gen의 Active 기능에 비해 매우 불편하고 Frame이 없이도 모델링이 불가능하진 않기 때문에, 사용자에 따라 필요한 Frame만 설정하여 사용하는 경우도 있습니다.
또한 건물의 규모가 작다면 Frame을 사용하지 않고 모든 노드와 부재에 접근할 수도 있습니다.
그럼에도 불구하고 Frame을 사용하는 것이 다방면에서 편리하기 때문에, Frame을 사용하는 것을 권장합니다.

본 업무절차서에서는 모든 부재의 Frame을 생성하여 모델링하는 방법을 소개합니다.

.. topic:: What to do

   이름만 입력된 비어있는 Frame을 먼저 생성한 후, 비어있는 Frame에 노드와 부재를 추가할 것입니다.

   1. :guilabel:`Add or Delete Frames`\를 클릭합니다. 생성된 창에서 :kbd:`New`\를 클릭합니다.

      .. figure:: _static/images/3_create_frames_name.gif
         :align: center

      Data Conversion Sheets의 Input_Naming 시트를 확인합니다. 이 시트의 ``Frame`` 열에 생성된 가장 첫 열, 첫 행의 이름을 Perform-3D에 입력합니다.

      .. figure:: _static/images/3_create_frames_Naming_시트.png
         :align: center
         :scale: 80%

      입력한 후에 :kbd:`OK`\를 클릭하면 비어있는 Frame이 생성됩니다.

   2. 같은 방법으로 ``Frame`` 열에 생성된 이름을 첫번쨰 열부터 차례대로 모두 입력합니다. 다만, 모델링에 필요없다고 판단되는 경우에는 생성하지 않아도 됩니다.

   3. 모든 Frame이 생성되면, Frame에 해당하는 노드와 부재를 추가합니다.
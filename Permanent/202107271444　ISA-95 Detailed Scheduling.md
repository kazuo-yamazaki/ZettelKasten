Operations Managing Categories の一つであり、Detailed Schedulingは[[202108010720 ISA-95 Operation Schedule|Operation Schedule]]をWork Scheduleに変換することが主たる目的である。

Detailed Scheduling アクティビティはリソース（人財、材料、機器）が利用可能か、資質が問題ないか判断して、Operation ScheduleをWork Scheduleすなわち、Work RequestとJob Orderに展開して他のアクティビティに提供する。

Work Scheduleに展開するためには、Production definition managementからWork masterを取得し、生産に必要なリソースが何かを判断し、メンテナンスオペレーションマネージメントや品質オペレーションマネージメント、インベントリーオペレーションマネージメントなどからデータを取得し、総合的に必要なリソースが使える状況を判断し、利用するリソースを予約しなければならない。

また計画通り生産が進んでいない場合には、再スケジュールする必要があるため、計画された生産と、実際の生産の差異を把握する必要がある。このためProduction Trackingアクティビティから実績データを取得する。

さらに、仮説シミュレーションの実行を行い、最適なスケジューリングができているかを確認する必要がある。

# Prev
[[202107271320 ISA-95 Production Resource Managment]]
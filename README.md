# Helloworld
select sum(balance) from t_user_asset_snapshot where coin_code = 'LAT' and snapshot_time = '2020-05-06 00:00:00.000' and account_type = 0;
select sum(balance) from t_user_asset_snapshot where coin_code = 'LAT' and snapshot_time = '2020-05-06 00:00:00.000' and account_type = 1;
select sum(balance) from t_user_asset_snapshot where coin_code = 'LAT' and snapshot_time = '2020-05-06 00:00:00.000' and account_type = 2;

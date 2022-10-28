
BatchedBancorMarketMaker._currentBatchId() (contracts/BatchedBancorMarketMaker.sol#424-426) performs a multiplication on the result of a division:
        -(block.number.div(batchBlocks)).mul(batchBlocks) (contracts/BatchedBancorMarketMaker.sol#425)
BatchedBancorMarketMaker._claimSellOrder(address,uint256,address) (contracts/BatchedBancorMarketMaker.sol#781-799) performs a multiplication on the result of a division:
        -saleReturn = (batch.sellers[_seller].mul(batch.totalSellReturn)).div(batch.totalSellSpend) (contracts/BatchedBancorMarketMaker.sol#783)
        -fee = saleReturn.mul(metaBatches[_batchId].sellFeePct).div(PCT_BASE) (contracts/BatchedBancorMarketMaker.sol#784)
BancorFormula.optimalLog(uint256) (contracts/bancor-formula/BancorFormula.sol#456-484) performs a multiplication on the result of a division:
        -x = x * FIXED_1 / 0xd3094c70f034de4b96ff7d5b6f99fcd8 (contracts/bancor-formula/BancorFormula.sol#463)
        -x = x * FIXED_1 / 0xa45af1e1f40c333b3de1db4dd55f29a7 (contracts/bancor-formula/BancorFormula.sol#464)
BancorFormula.optimalLog(uint256) (contracts/bancor-formula/BancorFormula.sol#456-484) performs a multiplication on the result of a division:
        -x = x * FIXED_1 / 0xd3094c70f034de4b96ff7d5b6f99fcd8 (contracts/bancor-formula/BancorFormula.sol#463)
        -x = x * FIXED_1 / 0x910b022db7ae67ce76b441c27035c6a1 (contracts/bancor-formula/BancorFormula.sol#465)
BancorFormula.optimalLog(uint256) (contracts/bancor-formula/BancorFormula.sol#456-484) performs a multiplication on the result of a division:
        -x = x * FIXED_1 / 0x910b022db7ae67ce76b441c27035c6a1 (contracts/bancor-formula/BancorFormula.sol#465)
        -x = x * FIXED_1 / 0x88415abbe9a76bead8d00cf112e4d4a8 (contracts/bancor-formula/BancorFormula.sol#466)
BancorFormula.optimalLog(uint256) (contracts/bancor-formula/BancorFormula.sol#456-484) performs a multiplication on the result of a division:
        -x = x * FIXED_1 / 0x88415abbe9a76bead8d00cf112e4d4a8 (contracts/bancor-formula/BancorFormula.sol#466)
        -x = x * FIXED_1 / 0x84102b00893f64c705e841d5d4064bd3 (contracts/bancor-formula/BancorFormula.sol#467)
BancorFormula.optimalLog(uint256) (contracts/bancor-formula/BancorFormula.sol#456-484) performs a multiplication on the result of a division:
        -x = x * FIXED_1 / 0x84102b00893f64c705e841d5d4064bd3 (contracts/bancor-formula/BancorFormula.sol#467)
        -x = x * FIXED_1 / 0x8204055aaef1c8bd5c3259f4822735a2 (contracts/bancor-formula/BancorFormula.sol#468)
BancorFormula.optimalLog(uint256) (contracts/bancor-formula/BancorFormula.sol#456-484) performs a multiplication on the result of a division:
        -x = x * FIXED_1 / 0x8204055aaef1c8bd5c3259f4822735a2 (contracts/bancor-formula/BancorFormula.sol#468)
        -x = x * FIXED_1 / 0x810100ab00222d861931c15e39b44e99 (contracts/bancor-formula/BancorFormula.sol#469)
BancorFormula.optimalLog(uint256) (contracts/bancor-formula/BancorFormula.sol#456-484) performs a multiplication on the result of a division:
        -x = x * FIXED_1 / 0x810100ab00222d861931c15e39b44e99 (contracts/bancor-formula/BancorFormula.sol#469)
        -x = x * FIXED_1 / 0x808040155aabbbe9451521693554f733 (contracts/bancor-formula/BancorFormula.sol#470)
BancorFormula.optimalLog(uint256) (contracts/bancor-formula/BancorFormula.sol#456-484) performs a multiplication on the result of a division:
        -w = y * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#473)
        -z = z * w / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#474)
BancorFormula.optimalLog(uint256) (contracts/bancor-formula/BancorFormula.sol#456-484) performs a multiplication on the result of a division:
        -z = z * w / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#474)
        -res += z * (0x0aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa - y) / 0x200000000000000000000000000000000 (contracts/bancor-formula/BancorFormula.sol#475)
BancorFormula.optimalLog(uint256) (contracts/bancor-formula/BancorFormula.sol#456-484) performs a multiplication on the result of a division:
        -w = y * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#473)
        -z = z * w / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#474)
        -z = z * w / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#475)
BancorFormula.optimalLog(uint256) (contracts/bancor-formula/BancorFormula.sol#456-484) performs a multiplication on the result of a division:
        -z = z * w / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#475)
        -res += z * (0x099999999999999999999999999999999 - y) / 0x300000000000000000000000000000000 (contracts/bancor-formula/BancorFormula.sol#476)
BancorFormula.optimalLog(uint256) (contracts/bancor-formula/BancorFormula.sol#456-484) performs a multiplication on the result of a division:
        -w = y * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#473)
        -z = z * w / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#475)
        -z = z * w / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#476)
BancorFormula.optimalLog(uint256) (contracts/bancor-formula/BancorFormula.sol#456-484) performs a multiplication on the result of a division:
        -z = z * w / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#476)
        -res += z * (0x092492492492492492492492492492492 - y) / 0x400000000000000000000000000000000 (contracts/bancor-formula/BancorFormula.sol#477)
BancorFormula.optimalLog(uint256) (contracts/bancor-formula/BancorFormula.sol#456-484) performs a multiplication on the result of a division:
        -w = y * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#473)
        -z = z * w / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#476)
        -z = z * w / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#477)
BancorFormula.optimalLog(uint256) (contracts/bancor-formula/BancorFormula.sol#456-484) performs a multiplication on the result of a division:
        -z = z * w / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#477)
        -res += z * (0x08e38e38e38e38e38e38e38e38e38e38e - y) / 0x500000000000000000000000000000000 (contracts/bancor-formula/BancorFormula.sol#478)
BancorFormula.optimalLog(uint256) (contracts/bancor-formula/BancorFormula.sol#456-484) performs a multiplication on the result of a division:
        -w = y * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#473)
        -z = z * w / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#477)
        -z = z * w / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#478)
BancorFormula.optimalLog(uint256) (contracts/bancor-formula/BancorFormula.sol#456-484) performs a multiplication on the result of a division:
        -z = z * w / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#478)
        -res += z * (0x08ba2e8ba2e8ba2e8ba2e8ba2e8ba2e8b - y) / 0x600000000000000000000000000000000 (contracts/bancor-formula/BancorFormula.sol#479)
BancorFormula.optimalLog(uint256) (contracts/bancor-formula/BancorFormula.sol#456-484) performs a multiplication on the result of a division:
        -w = y * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#473)
        -z = z * w / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#478)
        -z = z * w / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#479)
BancorFormula.optimalLog(uint256) (contracts/bancor-formula/BancorFormula.sol#456-484) performs a multiplication on the result of a division:
        -z = z * w / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#479)
        -res += z * (0x089d89d89d89d89d89d89d89d89d89d89 - y) / 0x700000000000000000000000000000000 (contracts/bancor-formula/BancorFormula.sol#480)
BancorFormula.optimalLog(uint256) (contracts/bancor-formula/BancorFormula.sol#456-484) performs a multiplication on the result of a division:
        -w = y * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#473)
        -z = z * w / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#479)
        -z = z * w / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#480)
BancorFormula.optimalLog(uint256) (contracts/bancor-formula/BancorFormula.sol#456-484) performs a multiplication on the result of a division:
        -z = z * w / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#480)
        -res += z * (0x088888888888888888888888888888888 - y) / 0x800000000000000000000000000000000 (contracts/bancor-formula/BancorFormula.sol#481)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) performs a multiplication on the result of a division:
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#504)
        -res += z * 0x10e1b3be415a0000 (contracts/bancor-formula/BancorFormula.sol#504)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) performs a multiplication on the result of a division:
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#504)
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#505)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) performs a multiplication on the result of a division:
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#505)
        -res += z * 0x05a0913f6b1e0000 (contracts/bancor-formula/BancorFormula.sol#505)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) performs a multiplication on the result of a division:
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#505)
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#506)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) performs a multiplication on the result of a division:
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#506)
        -res += z * 0x0168244fdac78000 (contracts/bancor-formula/BancorFormula.sol#506)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) performs a multiplication on the result of a division:
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#506)
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#507)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) performs a multiplication on the result of a division:
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#507)
        -res += z * 0x004807432bc18000 (contracts/bancor-formula/BancorFormula.sol#507)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) performs a multiplication on the result of a division:
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#507)
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#508)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) performs a multiplication on the result of a division:
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#508)
        -res += z * 0x000c0135dca04000 (contracts/bancor-formula/BancorFormula.sol#508)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) performs a multiplication on the result of a division:
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#508)
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#509)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) performs a multiplication on the result of a division:
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#509)
        -res += z * 0x0001b707b1cdc000 (contracts/bancor-formula/BancorFormula.sol#509)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) performs a multiplication on the result of a division:
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#509)
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#510)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) performs a multiplication on the result of a division:
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#510)
        -res += z * 0x000036e0f639b800 (contracts/bancor-formula/BancorFormula.sol#510)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) performs a multiplication on the result of a division:
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#510)
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#511)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) performs a multiplication on the result of a division:
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#511)
        -res += z * 0x00000618fee9f800 (contracts/bancor-formula/BancorFormula.sol#511)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) performs a multiplication on the result of a division:
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#511)
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#512)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) performs a multiplication on the result of a division:
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#512)
        -res += z * 0x0000009c197dcc00 (contracts/bancor-formula/BancorFormula.sol#512)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) performs a multiplication on the result of a division:
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#512)
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#513)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) performs a multiplication on the result of a division:
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#513)
        -res += z * 0x0000000e30dce400 (contracts/bancor-formula/BancorFormula.sol#513)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) performs a multiplication on the result of a division:
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#513)
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#514)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) performs a multiplication on the result of a division:
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#514)
        -res += z * 0x000000012ebd1300 (contracts/bancor-formula/BancorFormula.sol#514)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) performs a multiplication on the result of a division:
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#514)
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#515)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) performs a multiplication on the result of a division:
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#515)
        -res += z * 0x0000000017499f00 (contracts/bancor-formula/BancorFormula.sol#515)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) performs a multiplication on the result of a division:
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#515)
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#516)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) performs a multiplication on the result of a division:
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#516)
        -res += z * 0x0000000001a9d480 (contracts/bancor-formula/BancorFormula.sol#516)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) performs a multiplication on the result of a division:
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#516)
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#517)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) performs a multiplication on the result of a division:
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#517)
        -res += z * 0x00000000001c6380 (contracts/bancor-formula/BancorFormula.sol#517)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) performs a multiplication on the result of a division:
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#517)
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#518)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) performs a multiplication on the result of a division:
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#518)
        -res += z * 0x000000000001c638 (contracts/bancor-formula/BancorFormula.sol#518)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) performs a multiplication on the result of a division:
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#518)
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#519)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) performs a multiplication on the result of a division:
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#519)
        -res += z * 0x0000000000001ab8 (contracts/bancor-formula/BancorFormula.sol#519)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) performs a multiplication on the result of a division:
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#519)
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#520)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) performs a multiplication on the result of a division:
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#520)
        -res += z * 0x000000000000017c (contracts/bancor-formula/BancorFormula.sol#520)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) performs a multiplication on the result of a division:
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#520)
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#521)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) performs a multiplication on the result of a division:
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#521)
        -res += z * 0x0000000000000014 (contracts/bancor-formula/BancorFormula.sol#521)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) performs a multiplication on the result of a division:
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#521)
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#522)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) performs a multiplication on the result of a division:
        -z = z * y / FIXED_1 (contracts/bancor-formula/BancorFormula.sol#522)
        -res += z * 0x0000000000000001 (contracts/bancor-formula/BancorFormula.sol#522)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) performs a multiplication on the result of a division:
        -res = res * 0x1c3d6a24ed82218787d624d3e5eba95f9 / 0x18ebef9eac820ae8682b9793ac6d1e776 (contracts/bancor-formula/BancorFormula.sol#525)
        -res = res * 0x18ebef9eac820ae8682b9793ac6d1e778 / 0x1368b2fc6f9609fe7aceb46aa619baed4 (contracts/bancor-formula/BancorFormula.sol#526)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) performs a multiplication on the result of a division:
        -res = res * 0x18ebef9eac820ae8682b9793ac6d1e778 / 0x1368b2fc6f9609fe7aceb46aa619baed4 (contracts/bancor-formula/BancorFormula.sol#526)
        -res = res * 0x1368b2fc6f9609fe7aceb46aa619baed5 / 0x0bc5ab1b16779be3575bd8f0520a9f21f (contracts/bancor-formula/BancorFormula.sol#527)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) performs a multiplication on the result of a division:
        -res = res * 0x1368b2fc6f9609fe7aceb46aa619baed5 / 0x0bc5ab1b16779be3575bd8f0520a9f21f (contracts/bancor-formula/BancorFormula.sol#527)
        -res = res * 0x0bc5ab1b16779be3575bd8f0520a9f21e / 0x0454aaa8efe072e7f6ddbab84b40a55c9 (contracts/bancor-formula/BancorFormula.sol#528)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) performs a multiplication on the result of a division:
        -res = res * 0x0bc5ab1b16779be3575bd8f0520a9f21e / 0x0454aaa8efe072e7f6ddbab84b40a55c9 (contracts/bancor-formula/BancorFormula.sol#528)
        -res = res * 0x0454aaa8efe072e7f6ddbab84b40a55c5 / 0x00960aadc109e7a3bf4578099615711ea (contracts/bancor-formula/BancorFormula.sol#529)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) performs a multiplication on the result of a division:
        -res = res * 0x0454aaa8efe072e7f6ddbab84b40a55c5 / 0x00960aadc109e7a3bf4578099615711ea (contracts/bancor-formula/BancorFormula.sol#529)
        -res = res * 0x00960aadc109e7a3bf4578099615711d7 / 0x0002bf84208204f5977f9a8cf01fdce3d (contracts/bancor-formula/BancorFormula.sol#530)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) performs a multiplication on the result of a division:
        -res = res * 0x00960aadc109e7a3bf4578099615711d7 / 0x0002bf84208204f5977f9a8cf01fdce3d (contracts/bancor-formula/BancorFormula.sol#530)
        -res = res * 0x0002bf84208204f5977f9a8cf01fdc307 / 0x0000003c6ab775dd0b95b4cbee7e65d11 (contracts/bancor-formula/BancorFormula.sol#531)
Reference: https://github.com/crytic/slither/wiki/Detector-Documentation#divide-before-multiply

BatchedBancorMarketMaker._slippageIsValid(BatchedBancorMarketMaker.Batch) (contracts/BatchedBancorMarketMaker.sol#483-493) uses a dangerous strict equality:
        - staticPricePPM == 0 (contracts/BatchedBancorMarketMaker.sol#488)
Reference: https://github.com/crytic/slither/wiki/Detector-Documentation#dangerous-strict-equalities

Reentrancy in BatchedBancorMarketMaker._openBuyOrder(address,address,uint256) (contracts/BatchedBancorMarketMaker.sol#703-735):
        External calls:
        - ERC20(_collateral).safeTransferFrom(_buyer,beneficiary,fee) (contracts/BatchedBancorMarketMaker.sol#712)
        - ERC20(_collateral).safeTransferFrom(_buyer,address(this),value) (contracts/BatchedBancorMarketMaker.sol#714)
        State variables written after the call(s):
        - collateralsToBeClaimed[_collateral] = collateralsToBeClaimed[_collateral].sub(deprecatedSellReturn).add(batch.totalSellReturn) (contracts/BatchedBancorMarketMaker.sol#729)
        - tokensToBeMinted = tokensToBeMinted.sub(deprecatedBuyReturn).add(batch.totalBuyReturn) (contracts/BatchedBancorMarketMaker.sol#728)
Reentrancy in BatchedBancorMarketMaker._openSellOrder(address,address,uint256) (contracts/BatchedBancorMarketMaker.sol#737-764):
        External calls:
        - token.burnFrom(_seller,_amount) (contracts/BatchedBancorMarketMaker.sol#742)
        State variables written after the call(s):
        - collateralsToBeClaimed[_collateral] = collateralsToBeClaimed[_collateral].sub(deprecatedSellReturn).add(batch.totalSellReturn) (contracts/BatchedBancorMarketMaker.sol#757)
        - tokensToBeMinted = tokensToBeMinted.sub(deprecatedBuyReturn).add(batch.totalBuyReturn) (contracts/BatchedBancorMarketMaker.sol#756)
Reference: https://github.com/crytic/slither/wiki/Detector-Documentation#reentrancy-vulnerabilities-1

BancorFormula.optimalExp(uint256).y (contracts/bancor-formula/BancorFormula.sol#500) is a local variable never initialized
BancorFormula.optimalLog(uint256).y (contracts/bancor-formula/BancorFormula.sol#459) is a local variable never initialized
Reference: https://github.com/crytic/slither/wiki/Detector-Documentation#uninitialized-local-variables

AccessControlEnumerable._grantRole(bytes32,address) (node_modules/@openzeppelin/contracts/access/AccessControlEnumerable.sol#52-55) ignores return value by _roleMembers[role].add(account) (node_modules/@openzeppelin/contracts/access/AccessControlEnumerable.sol#54)
AccessControlEnumerable._revokeRole(bytes32,address) (node_modules/@openzeppelin/contracts/access/AccessControlEnumerable.sol#60-63) ignores return value by _roleMembers[role].remove(account) (node_modules/@openzeppelin/contracts/access/AccessControlEnumerable.sol#62)
ERC721._checkOnERC721Received(address,address,uint256,bytes) (node_modules/@openzeppelin/contracts/token/ERC721/ERC721.sol#394-416) ignores return value by IERC721Receiver(to).onERC721Received(_msgSender(),from,tokenId,data) (node_modules/@openzeppelin/contracts/token/ERC721/ERC721.sol#401-412)
Reference: https://github.com/crytic/slither/wiki/Detector-Documentation#unused-return

BatchedBancorMarketMaker.open(bool)._status (contracts/BatchedBancorMarketMaker.sol#184) shadows:
        - ReentrancyGuard._status (node_modules/@openzeppelin/contracts/security/ReentrancyGuard.sol#37) (state variable)
BatchedBancorMarketMaker._open(bool)._status (contracts/BatchedBancorMarketMaker.sol#622) shadows:
        - ReentrancyGuard._status (node_modules/@openzeppelin/contracts/security/ReentrancyGuard.sol#37) (state variable)
ERC20Token.constructor(address,uint256,string,string).name (contracts/ERC20Token.sol#31) shadows:
        - ERC20.name() (node_modules/@openzeppelin/contracts/token/ERC20/ERC20.sol#62-64) (function)
        - IERC20Metadata.name() (node_modules/@openzeppelin/contracts/token/ERC20/extensions/IERC20Metadata.sol#17) (function)
ERC20Token.constructor(address,uint256,string,string).symbol (contracts/ERC20Token.sol#31) shadows:
        - ERC20.symbol() (node_modules/@openzeppelin/contracts/token/ERC20/ERC20.sol#70-72) (function)
        - IERC20Metadata.symbol() (node_modules/@openzeppelin/contracts/token/ERC20/extensions/IERC20Metadata.sol#22) (function)
Reference: https://github.com/crytic/slither/wiki/Detector-Documentation#local-variable-shadowing

Variable 'ERC721._checkOnERC721Received(address,address,uint256,bytes).retval (node_modules/@openzeppelin/contracts/token/ERC721/ERC721.sol#401)' in ERC721._checkOnERC721Received(address,address,uint256,bytes) (node_modules/@openzeppelin/contracts/token/ERC721/ERC721.sol#394-416) potentially used before declaration: retval == IERC721Receiver.onERC721Received.selector (node_modules/@openzeppelin/contracts/token/ERC721/ERC721.sol#402)
Variable 'ERC721._checkOnERC721Received(address,address,uint256,bytes).reason (node_modules/@openzeppelin/contracts/token/ERC721/ERC721.sol#403)' in ERC721._checkOnERC721Received(address,address,uint256,bytes) (node_modules/@openzeppelin/contracts/token/ERC721/ERC721.sol#394-416) potentially used before declaration: reason.length == 0 (node_modules/@openzeppelin/contracts/token/ERC721/ERC721.sol#404)
Variable 'ERC721._checkOnERC721Received(address,address,uint256,bytes).reason (node_modules/@openzeppelin/contracts/token/ERC721/ERC721.sol#403)' in ERC721._checkOnERC721Received(address,address,uint256,bytes) (node_modules/@openzeppelin/contracts/token/ERC721/ERC721.sol#394-416) potentially used before declaration: revert(uint256,uint256)(32 + reason,mload(uint256)(reason)) (node_modules/@openzeppelin/contracts/token/ERC721/ERC721.sol#409)
Reference: https://github.com/crytic/slither/wiki/Detector-Documentation#pre-declaration-usage-of-local-variables

Reentrancy in BatchedBancorMarketMaker._claimBuyOrder(address,uint256,address) (contracts/BatchedBancorMarketMaker.sol#766-779):
        External calls:
        - token.mint(_buyer,buyReturn) (contracts/BatchedBancorMarketMaker.sol#775)
        Event emitted after the call(s):
        - ClaimBuyOrder(_buyer,_batchId,_collateral,buyReturn) (contracts/BatchedBancorMarketMaker.sol#778)
Reentrancy in BatchedBancorMarketMaker._claimCancelledBuyOrder(address,uint256,address) (contracts/BatchedBancorMarketMaker.sol#801-814):
        External calls:
        - ERC20(_collateral).safeTransfer(_buyer,value) (contracts/BatchedBancorMarketMaker.sol#810)
        Event emitted after the call(s):
        - ClaimCancelledBuyOrder(_buyer,_batchId,_collateral,value) (contracts/BatchedBancorMarketMaker.sol#813)
Reentrancy in BatchedBancorMarketMaker._claimCancelledSellOrder(address,uint256,address) (contracts/BatchedBancorMarketMaker.sol#816-829):
        External calls:
        - token.mint(_seller,amount) (contracts/BatchedBancorMarketMaker.sol#825)
        Event emitted after the call(s):
        - ClaimCancelledSellOrder(_seller,_batchId,_collateral,amount) (contracts/BatchedBancorMarketMaker.sol#828)
Reentrancy in BatchedBancorMarketMaker._claimSellOrder(address,uint256,address) (contracts/BatchedBancorMarketMaker.sol#781-799):
        External calls:
        - ERC20(_collateral).safeTransfer(_seller,value) (contracts/BatchedBancorMarketMaker.sol#791)
        - ERC20(_collateral).safeTransfer(beneficiary,fee) (contracts/BatchedBancorMarketMaker.sol#794)
        Event emitted after the call(s):
        - ClaimSellOrder(_seller,_batchId,_collateral,fee,value) (contracts/BatchedBancorMarketMaker.sol#798)
Reentrancy in BatchedBancorMarketMaker._openBuyOrder(address,address,uint256) (contracts/BatchedBancorMarketMaker.sol#703-735):
        External calls:
        - ERC20(_collateral).safeTransferFrom(_buyer,beneficiary,fee) (contracts/BatchedBancorMarketMaker.sol#712)
        - ERC20(_collateral).safeTransferFrom(_buyer,address(this),value) (contracts/BatchedBancorMarketMaker.sol#714)
        Event emitted after the call(s):
        - OpenBuyOrder(_buyer,batchId,_collateral,fee,value) (contracts/BatchedBancorMarketMaker.sol#734)
        - UpdatePricing(_batchId,_collateral,batch.totalBuySpend,batch.totalBuyReturn,batch.totalSellSpend,batch.totalSellReturn) (contracts/BatchedBancorMarketMaker.sol#898)
                - _updatePricing(batch,batchId,_collateral) (contracts/BatchedBancorMarketMaker.sol#725)
Reentrancy in BatchedBancorMarketMaker._openSellOrder(address,address,uint256) (contracts/BatchedBancorMarketMaker.sol#737-764):
        External calls:
        - token.burnFrom(_seller,_amount) (contracts/BatchedBancorMarketMaker.sol#742)
        Event emitted after the call(s):
        - OpenSellOrder(_seller,batchId,_collateral,_amount) (contracts/BatchedBancorMarketMaker.sol#763)
        - UpdatePricing(_batchId,_collateral,batch.totalBuySpend,batch.totalBuyReturn,batch.totalSellSpend,batch.totalSellReturn) (contracts/BatchedBancorMarketMaker.sol#898)
                - _updatePricing(batch,batchId,_collateral) (contracts/BatchedBancorMarketMaker.sol#753)
Reference: https://github.com/crytic/slither/wiki/Detector-Documentation#reentrancy-vulnerabilities-3

ERC721._checkOnERC721Received(address,address,uint256,bytes) (node_modules/@openzeppelin/contracts/token/ERC721/ERC721.sol#394-416) uses assembly
        - INLINE ASM (node_modules/@openzeppelin/contracts/token/ERC721/ERC721.sol#408-410)
Address.verifyCallResult(bool,bytes,string) (node_modules/@openzeppelin/contracts/utils/Address.sol#201-221) uses assembly
        - INLINE ASM (node_modules/@openzeppelin/contracts/utils/Address.sol#213-216)
EnumerableSet.values(EnumerableSet.AddressSet) (node_modules/@openzeppelin/contracts/utils/structs/EnumerableSet.sol#282-292) uses assembly
        - INLINE ASM (node_modules/@openzeppelin/contracts/utils/structs/EnumerableSet.sol#287-289)
EnumerableSet.values(EnumerableSet.UintSet) (node_modules/@openzeppelin/contracts/utils/structs/EnumerableSet.sol#356-366) uses assembly
        - INLINE ASM (node_modules/@openzeppelin/contracts/utils/structs/EnumerableSet.sol#361-363)
Reference: https://github.com/crytic/slither/wiki/Detector-Documentation#assembly-usage

Different versions of Solidity are used:
        - Version used: ['^0.8.0', '^0.8.1', '^0.8.9']
        - ^0.8.0 (node_modules/@openzeppelin/contracts/access/AccessControl.sol#4)
        - ^0.8.0 (node_modules/@openzeppelin/contracts/access/AccessControlEnumerable.sol#4)
        - ^0.8.0 (node_modules/@openzeppelin/contracts/access/IAccessControl.sol#4)
        - ^0.8.0 (node_modules/@openzeppelin/contracts/access/IAccessControlEnumerable.sol#4)
        - ^0.8.0 (node_modules/@openzeppelin/contracts/security/Pausable.sol#4)
        - ^0.8.0 (node_modules/@openzeppelin/contracts/security/ReentrancyGuard.sol#4)
        - ^0.8.0 (node_modules/@openzeppelin/contracts/token/ERC20/ERC20.sol#4)
        - ^0.8.0 (node_modules/@openzeppelin/contracts/token/ERC20/IERC20.sol#4)
        - ^0.8.0 (node_modules/@openzeppelin/contracts/token/ERC20/extensions/ERC20Burnable.sol#4)
        - ^0.8.0 (node_modules/@openzeppelin/contracts/token/ERC20/extensions/ERC20Pausable.sol#4)
        - ^0.8.0 (node_modules/@openzeppelin/contracts/token/ERC20/extensions/IERC20Metadata.sol#4)
        - ^0.8.0 (node_modules/@openzeppelin/contracts/token/ERC20/extensions/draft-IERC20Permit.sol#4)
        - ^0.8.0 (node_modules/@openzeppelin/contracts/token/ERC20/utils/SafeERC20.sol#4)
        - ^0.8.0 (node_modules/@openzeppelin/contracts/token/ERC721/ERC721.sol#4)
        - ^0.8.0 (node_modules/@openzeppelin/contracts/token/ERC721/IERC721.sol#4)
        - ^0.8.0 (node_modules/@openzeppelin/contracts/token/ERC721/IERC721Receiver.sol#4)
        - ^0.8.0 (node_modules/@openzeppelin/contracts/token/ERC721/extensions/IERC721Metadata.sol#4)
        - ^0.8.1 (node_modules/@openzeppelin/contracts/utils/Address.sol#4)
        - ^0.8.0 (node_modules/@openzeppelin/contracts/utils/Context.sol#4)
        - ^0.8.0 (node_modules/@openzeppelin/contracts/utils/Strings.sol#4)
        - ^0.8.0 (node_modules/@openzeppelin/contracts/utils/introspection/ERC165.sol#4)
        - ^0.8.0 (node_modules/@openzeppelin/contracts/utils/introspection/IERC165.sol#4)
        - ^0.8.0 (node_modules/@openzeppelin/contracts/utils/math/SafeMath.sol#4)
        - ^0.8.0 (node_modules/@openzeppelin/contracts/utils/structs/EnumerableSet.sol#4)
        - ^0.8.9 (contracts/BatchedBancorMarketMaker.sol#2)
        - ^0.8.9 (contracts/ERC20Token.sol#2)
        - ^0.8.0 (contracts/TestDAI.sol#2)
        - ^0.8.0 (contracts/bancor-formula/BancorFormula.sol#2)
        - ^0.8.0 (contracts/bancor-formula/interfaces/IBancorFormula.sol#2)
        - ^0.8.0 (contracts/bancor-formula/utils/Utils.sol#2)
Reference: https://github.com/crytic/slither/wiki/Detector-Documentation#different-pragma-directives-are-used

Pragma version^0.8.0 (node_modules/@openzeppelin/contracts/access/AccessControl.sol#4) allows old versions
Pragma version^0.8.0 (node_modules/@openzeppelin/contracts/access/AccessControlEnumerable.sol#4) allows old versions
Pragma version^0.8.0 (node_modules/@openzeppelin/contracts/access/IAccessControl.sol#4) allows old versions
Pragma version^0.8.0 (node_modules/@openzeppelin/contracts/access/IAccessControlEnumerable.sol#4) allows old versions
Pragma version^0.8.0 (node_modules/@openzeppelin/contracts/security/Pausable.sol#4) allows old versions
Pragma version^0.8.0 (node_modules/@openzeppelin/contracts/security/ReentrancyGuard.sol#4) allows old versions
Pragma version^0.8.0 (node_modules/@openzeppelin/contracts/token/ERC20/ERC20.sol#4) allows old versions
Pragma version^0.8.0 (node_modules/@openzeppelin/contracts/token/ERC20/IERC20.sol#4) allows old versions
Pragma version^0.8.0 (node_modules/@openzeppelin/contracts/token/ERC20/extensions/ERC20Burnable.sol#4) allows old versions
Pragma version^0.8.0 (node_modules/@openzeppelin/contracts/token/ERC20/extensions/ERC20Pausable.sol#4) allows old versions
Pragma version^0.8.0 (node_modules/@openzeppelin/contracts/token/ERC20/extensions/IERC20Metadata.sol#4) allows old versions
Pragma version^0.8.0 (node_modules/@openzeppelin/contracts/token/ERC20/extensions/draft-IERC20Permit.sol#4) allows old versions
Pragma version^0.8.0 (node_modules/@openzeppelin/contracts/token/ERC20/utils/SafeERC20.sol#4) allows old versions
Pragma version^0.8.0 (node_modules/@openzeppelin/contracts/token/ERC721/ERC721.sol#4) allows old versions
Pragma version^0.8.0 (node_modules/@openzeppelin/contracts/token/ERC721/IERC721.sol#4) allows old versions
Pragma version^0.8.0 (node_modules/@openzeppelin/contracts/token/ERC721/IERC721Receiver.sol#4) allows old versions
Pragma version^0.8.0 (node_modules/@openzeppelin/contracts/token/ERC721/extensions/IERC721Metadata.sol#4) allows old versions
Pragma version^0.8.1 (node_modules/@openzeppelin/contracts/utils/Address.sol#4) allows old versions
Pragma version^0.8.0 (node_modules/@openzeppelin/contracts/utils/Context.sol#4) allows old versions
Pragma version^0.8.0 (node_modules/@openzeppelin/contracts/utils/Strings.sol#4) allows old versions
Pragma version^0.8.0 (node_modules/@openzeppelin/contracts/utils/introspection/ERC165.sol#4) allows old versions
Pragma version^0.8.0 (node_modules/@openzeppelin/contracts/utils/introspection/IERC165.sol#4) allows old versions
Pragma version^0.8.0 (node_modules/@openzeppelin/contracts/utils/math/SafeMath.sol#4) allows old versions
Pragma version^0.8.0 (node_modules/@openzeppelin/contracts/utils/structs/EnumerableSet.sol#4) allows old versions
Pragma version^0.8.9 (contracts/BatchedBancorMarketMaker.sol#2) necessitates a version too recent to be trusted. Consider deploying with 0.6.12/0.7.6/0.8.7
Pragma version^0.8.9 (contracts/ERC20Token.sol#2) necessitates a version too recent to be trusted. Consider deploying with 0.6.12/0.7.6/0.8.7
Pragma version^0.8.0 (contracts/TestDAI.sol#2) allows old versions
Pragma version^0.8.0 (contracts/bancor-formula/BancorFormula.sol#2) allows old versions
Pragma version^0.8.0 (contracts/bancor-formula/interfaces/IBancorFormula.sol#2) allows old versions
Pragma version^0.8.0 (contracts/bancor-formula/utils/Utils.sol#2) allows old versions
solc-0.8.9 is not recommended for deployment
Reference: https://github.com/crytic/slither/wiki/Detector-Documentation#incorrect-versions-of-solidity

Low level call in Address.sendValue(address,uint256) (node_modules/@openzeppelin/contracts/utils/Address.sol#60-65):
        - (success) = recipient.call{value: amount}() (node_modules/@openzeppelin/contracts/utils/Address.sol#63)
Low level call in Address.functionCallWithValue(address,bytes,uint256,string) (node_modules/@openzeppelin/contracts/utils/Address.sol#128-139):
        - (success,returndata) = target.call{value: value}(data) (node_modules/@openzeppelin/contracts/utils/Address.sol#137)
Low level call in Address.functionStaticCall(address,bytes,string) (node_modules/@openzeppelin/contracts/utils/Address.sol#157-166):
        - (success,returndata) = target.staticcall(data) (node_modules/@openzeppelin/contracts/utils/Address.sol#164)
Low level call in Address.functionDelegateCall(address,bytes,string) (node_modules/@openzeppelin/contracts/utils/Address.sol#184-193):
        - (success,returndata) = target.delegatecall(data) (node_modules/@openzeppelin/contracts/utils/Address.sol#191)
Reference: https://github.com/crytic/slither/wiki/Detector-Documentation#low-level-calls

Function IERC20Permit.DOMAIN_SEPARATOR() (node_modules/@openzeppelin/contracts/token/ERC20/extensions/draft-IERC20Permit.sol#59) is not in mixedCase
Parameter BatchedBancorMarketMaker.open(bool)._status (contracts/BatchedBancorMarketMaker.sol#184) is not in mixedCase
Parameter BatchedBancorMarketMaker.updateFormula(IBancorFormula)._formula (contracts/BatchedBancorMarketMaker.sol#192) is not in mixedCase
Parameter BatchedBancorMarketMaker.updateBeneficiary(address)._beneficiary (contracts/BatchedBancorMarketMaker.sol#200) is not in mixedCase
Parameter BatchedBancorMarketMaker.updateFees(uint256,uint256)._buyFeePct (contracts/BatchedBancorMarketMaker.sol#211) is not in mixedCase
Parameter BatchedBancorMarketMaker.updateFees(uint256,uint256)._sellFeePct (contracts/BatchedBancorMarketMaker.sol#211) is not in mixedCase
Parameter BatchedBancorMarketMaker.addCollateralToken(address,uint256,uint256,uint32,uint256)._collateral (contracts/BatchedBancorMarketMaker.sol#227) is not in mixedCase
Parameter BatchedBancorMarketMaker.addCollateralToken(address,uint256,uint256,uint32,uint256)._virtualSupply (contracts/BatchedBancorMarketMaker.sol#227) is not in mixedCase
Parameter BatchedBancorMarketMaker.addCollateralToken(address,uint256,uint256,uint32,uint256)._virtualBalance (contracts/BatchedBancorMarketMaker.sol#227) is not in mixedCase
Parameter BatchedBancorMarketMaker.addCollateralToken(address,uint256,uint256,uint32,uint256)._reserveRatio (contracts/BatchedBancorMarketMaker.sol#227) is not in mixedCase
Parameter BatchedBancorMarketMaker.addCollateralToken(address,uint256,uint256,uint32,uint256)._slippage (contracts/BatchedBancorMarketMaker.sol#227) is not in mixedCase
Parameter BatchedBancorMarketMaker.removeCollateralToken(address)._collateral (contracts/BatchedBancorMarketMaker.sol#242) is not in mixedCase
Parameter BatchedBancorMarketMaker.updateCollateralToken(address,uint256,uint256,uint32,uint256)._collateral (contracts/BatchedBancorMarketMaker.sol#256) is not in mixedCase
Parameter BatchedBancorMarketMaker.updateCollateralToken(address,uint256,uint256,uint32,uint256)._virtualSupply (contracts/BatchedBancorMarketMaker.sol#256) is not in mixedCase
Parameter BatchedBancorMarketMaker.updateCollateralToken(address,uint256,uint256,uint32,uint256)._virtualBalance (contracts/BatchedBancorMarketMaker.sol#256) is not in mixedCase
Parameter BatchedBancorMarketMaker.updateCollateralToken(address,uint256,uint256,uint32,uint256)._reserveRatio (contracts/BatchedBancorMarketMaker.sol#256) is not in mixedCase
Parameter BatchedBancorMarketMaker.updateCollateralToken(address,uint256,uint256,uint32,uint256)._slippage (contracts/BatchedBancorMarketMaker.sol#256) is not in mixedCase
Parameter BatchedBancorMarketMaker.openBuyOrder(address,address,uint256)._buyer (contracts/BatchedBancorMarketMaker.sol#274) is not in mixedCase
Parameter BatchedBancorMarketMaker.openBuyOrder(address,address,uint256)._collateral (contracts/BatchedBancorMarketMaker.sol#274) is not in mixedCase
Parameter BatchedBancorMarketMaker.openBuyOrder(address,address,uint256)._value (contracts/BatchedBancorMarketMaker.sol#274) is not in mixedCase
Parameter BatchedBancorMarketMaker.openSellOrder(address,address,uint256)._seller (contracts/BatchedBancorMarketMaker.sol#289) is not in mixedCase
Parameter BatchedBancorMarketMaker.openSellOrder(address,address,uint256)._collateral (contracts/BatchedBancorMarketMaker.sol#289) is not in mixedCase
Parameter BatchedBancorMarketMaker.openSellOrder(address,address,uint256)._amount (contracts/BatchedBancorMarketMaker.sol#289) is not in mixedCase
Parameter BatchedBancorMarketMaker.claimBuyOrder(address,uint256,address)._buyer (contracts/BatchedBancorMarketMaker.sol#305) is not in mixedCase
Parameter BatchedBancorMarketMaker.claimBuyOrder(address,uint256,address)._batchId (contracts/BatchedBancorMarketMaker.sol#305) is not in mixedCase
Parameter BatchedBancorMarketMaker.claimBuyOrder(address,uint256,address)._collateral (contracts/BatchedBancorMarketMaker.sol#305) is not in mixedCase
Parameter BatchedBancorMarketMaker.claimSellOrder(address,uint256,address)._seller (contracts/BatchedBancorMarketMaker.sol#320) is not in mixedCase
Parameter BatchedBancorMarketMaker.claimSellOrder(address,uint256,address)._batchId (contracts/BatchedBancorMarketMaker.sol#320) is not in mixedCase
Parameter BatchedBancorMarketMaker.claimSellOrder(address,uint256,address)._collateral (contracts/BatchedBancorMarketMaker.sol#320) is not in mixedCase
Parameter BatchedBancorMarketMaker.claimCancelledBuyOrder(address,uint256,address)._buyer (contracts/BatchedBancorMarketMaker.sol#335) is not in mixedCase
Parameter BatchedBancorMarketMaker.claimCancelledBuyOrder(address,uint256,address)._batchId (contracts/BatchedBancorMarketMaker.sol#335) is not in mixedCase
Parameter BatchedBancorMarketMaker.claimCancelledBuyOrder(address,uint256,address)._collateral (contracts/BatchedBancorMarketMaker.sol#335) is not in mixedCase
Parameter BatchedBancorMarketMaker.claimCancelledSellOrder(address,uint256,address)._seller (contracts/BatchedBancorMarketMaker.sol#348) is not in mixedCase
Parameter BatchedBancorMarketMaker.claimCancelledSellOrder(address,uint256,address)._batchId (contracts/BatchedBancorMarketMaker.sol#348) is not in mixedCase
Parameter BatchedBancorMarketMaker.claimCancelledSellOrder(address,uint256,address)._collateral (contracts/BatchedBancorMarketMaker.sol#348) is not in mixedCase
Parameter BatchedBancorMarketMaker.getCollateralToken(address)._collateral (contracts/BatchedBancorMarketMaker.sol#361) is not in mixedCase
Parameter BatchedBancorMarketMaker.getBatch(uint256,address)._batchId (contracts/BatchedBancorMarketMaker.sol#367) is not in mixedCase
Parameter BatchedBancorMarketMaker.getBatch(uint256,address)._collateral (contracts/BatchedBancorMarketMaker.sol#367) is not in mixedCase
Parameter BatchedBancorMarketMaker.getCollateralPricePPM(address)._collateral (contracts/BatchedBancorMarketMaker.sol#387) is not in mixedCase
Parameter BatchedBancorMarketMaker.getStaticPricePPM(uint256,uint256,uint32)._supply (contracts/BatchedBancorMarketMaker.sol#391) is not in mixedCase
Parameter BatchedBancorMarketMaker.getStaticPricePPM(uint256,uint256,uint32)._balance (contracts/BatchedBancorMarketMaker.sol#391) is not in mixedCase
Parameter BatchedBancorMarketMaker.getStaticPricePPM(uint256,uint256,uint32)._reserveRatio (contracts/BatchedBancorMarketMaker.sol#391) is not in mixedCase
Parameter BatchedBancorMarketMaker.withdrawCollateral(address,uint256)._collateral (contracts/BatchedBancorMarketMaker.sol#397) is not in mixedCase
Parameter BatchedBancorMarketMaker.withdrawCollateral(address,uint256)._amount (contracts/BatchedBancorMarketMaker.sol#397) is not in mixedCase
Parameter BatchedBancorMarketMaker.withdrawNFT(address,uint256)._token (contracts/BatchedBancorMarketMaker.sol#402) is not in mixedCase
Parameter BatchedBancorMarketMaker.withdrawNFT(address,uint256)._tokenId (contracts/BatchedBancorMarketMaker.sol#402) is not in mixedCase
Parameter BatchedBancorMarketMaker.updateCurveSupply(uint256)._supply (contracts/BatchedBancorMarketMaker.sol#407) is not in mixedCase
Parameter BatchedBancorMarketMaker.updateMinCurveSupply(uint256)._minSupply (contracts/BatchedBancorMarketMaker.sol#411) is not in mixedCase
Parameter BancorFormula.calculatePurchaseReturn(uint256,uint256,uint32,uint256)._supply (contracts/bancor-formula/BancorFormula.sol#187) is not in mixedCase
Parameter BancorFormula.calculatePurchaseReturn(uint256,uint256,uint32,uint256)._reserveBalance (contracts/bancor-formula/BancorFormula.sol#187) is not in mixedCase
Parameter BancorFormula.calculatePurchaseReturn(uint256,uint256,uint32,uint256)._reserveRatio (contracts/bancor-formula/BancorFormula.sol#187) is not in mixedCase
Parameter BancorFormula.calculatePurchaseReturn(uint256,uint256,uint32,uint256)._depositAmount (contracts/bancor-formula/BancorFormula.sol#187) is not in mixedCase
Parameter BancorFormula.calculateSaleReturn(uint256,uint256,uint32,uint256)._supply (contracts/bancor-formula/BancorFormula.sol#221) is not in mixedCase
Parameter BancorFormula.calculateSaleReturn(uint256,uint256,uint32,uint256)._reserveBalance (contracts/bancor-formula/BancorFormula.sol#221) is not in mixedCase
Parameter BancorFormula.calculateSaleReturn(uint256,uint256,uint32,uint256)._reserveRatio (contracts/bancor-formula/BancorFormula.sol#221) is not in mixedCase
Parameter BancorFormula.calculateSaleReturn(uint256,uint256,uint32,uint256)._sellAmount (contracts/bancor-formula/BancorFormula.sol#221) is not in mixedCase
Parameter BancorFormula.calculateCrossReserveReturn(uint256,uint32,uint256,uint32,uint256)._fromReserveBalance (contracts/bancor-formula/BancorFormula.sol#262) is not in mixedCase
Parameter BancorFormula.calculateCrossReserveReturn(uint256,uint32,uint256,uint32,uint256)._fromReserveRatio (contracts/bancor-formula/BancorFormula.sol#262) is not in mixedCase
Parameter BancorFormula.calculateCrossReserveReturn(uint256,uint32,uint256,uint32,uint256)._toReserveBalance (contracts/bancor-formula/BancorFormula.sol#262) is not in mixedCase
Parameter BancorFormula.calculateCrossReserveReturn(uint256,uint32,uint256,uint32,uint256)._toReserveRatio (contracts/bancor-formula/BancorFormula.sol#262) is not in mixedCase
Parameter BancorFormula.calculateCrossReserveReturn(uint256,uint32,uint256,uint32,uint256)._amount (contracts/bancor-formula/BancorFormula.sol#262) is not in mixedCase
Parameter BancorFormula.power(uint256,uint256,uint32,uint32)._baseN (contracts/bancor-formula/BancorFormula.sol#296) is not in mixedCase
Parameter BancorFormula.power(uint256,uint256,uint32,uint32)._baseD (contracts/bancor-formula/BancorFormula.sol#296) is not in mixedCase
Parameter BancorFormula.power(uint256,uint256,uint32,uint32)._expN (contracts/bancor-formula/BancorFormula.sol#296) is not in mixedCase
Parameter BancorFormula.power(uint256,uint256,uint32,uint32)._expD (contracts/bancor-formula/BancorFormula.sol#296) is not in mixedCase
Parameter BancorFormula.floorLog2(uint256)._n (contracts/bancor-formula/BancorFormula.sol#349) is not in mixedCase
Parameter BancorFormula.findPositionInMaxExpArray(uint256)._x (contracts/bancor-formula/BancorFormula.sol#377) is not in mixedCase
Parameter BancorFormula.generalExp(uint256,uint8)._x (contracts/bancor-formula/BancorFormula.sol#405) is not in mixedCase
Parameter BancorFormula.generalExp(uint256,uint8)._precision (contracts/bancor-formula/BancorFormula.sol#405) is not in mixedCase
Parameter BancorFormula.calculateCrossConnectorReturn(uint256,uint32,uint256,uint32,uint256)._fromConnectorBalance (contracts/bancor-formula/BancorFormula.sol#539) is not in mixedCase
Parameter BancorFormula.calculateCrossConnectorReturn(uint256,uint32,uint256,uint32,uint256)._fromConnectorWeight (contracts/bancor-formula/BancorFormula.sol#539) is not in mixedCase
Parameter BancorFormula.calculateCrossConnectorReturn(uint256,uint32,uint256,uint32,uint256)._toConnectorBalance (contracts/bancor-formula/BancorFormula.sol#539) is not in mixedCase
Parameter BancorFormula.calculateCrossConnectorReturn(uint256,uint32,uint256,uint32,uint256)._toConnectorWeight (contracts/bancor-formula/BancorFormula.sol#539) is not in mixedCase
Parameter BancorFormula.calculateCrossConnectorReturn(uint256,uint32,uint256,uint32,uint256)._amount (contracts/bancor-formula/BancorFormula.sol#539) is not in mixedCase
Reference: https://github.com/crytic/slither/wiki/Detector-Documentation#conformance-to-solidity-naming-conventions

Variable BatchedBancorMarketMaker._poolBalanceIsSufficient(address)._collateral (contracts/BatchedBancorMarketMaker.sol#479) is too similar to BatchedBancorMarketMaker.collaterals (contracts/BatchedBancorMarketMaker.sol#94)
Variable BatchedBancorMarketMaker.addCollateralToken(address,uint256,uint256,uint32,uint256)._collateral (contracts/BatchedBancorMarketMaker.sol#227) is too similar to BatchedBancorMarketMaker.collaterals (contracts/BatchedBancorMarketMaker.sol#94)
Variable BatchedBancorMarketMaker._openBuyOrder(address,address,uint256)._collateral (contracts/BatchedBancorMarketMaker.sol#703) is too similar to BatchedBancorMarketMaker.collaterals (contracts/BatchedBancorMarketMaker.sol#94)
Variable BatchedBancorMarketMaker._userIsBuyer(uint256,address,address)._collateral (contracts/BatchedBancorMarketMaker.sol#469) is too similar to BatchedBancorMarketMaker.collaterals (contracts/BatchedBancorMarketMaker.sol#94)
Variable BatchedBancorMarketMaker._removeCollateralToken(address)._collateral (contracts/BatchedBancorMarketMaker.sol#673) is too similar to BatchedBancorMarketMaker.collaterals (contracts/BatchedBancorMarketMaker.sol#94)
Variable BatchedBancorMarketMaker.getCollateralPricePPM(address)._collateral (contracts/BatchedBancorMarketMaker.sol#387) is too similar to BatchedBancorMarketMaker.collaterals (contracts/BatchedBancorMarketMaker.sol#94)
Variable BatchedBancorMarketMaker.getBatch(uint256,address)._collateral (contracts/BatchedBancorMarketMaker.sol#367) is too similar to BatchedBancorMarketMaker.collaterals (contracts/BatchedBancorMarketMaker.sol#94)
Variable BatchedBancorMarketMaker.openSellOrder(address,address,uint256)._collateral (contracts/BatchedBancorMarketMaker.sol#289) is too similar to BatchedBancorMarketMaker.collaterals (contracts/BatchedBancorMarketMaker.sol#94)
Variable BatchedBancorMarketMaker._claimCancelledBuyOrder(address,uint256,address)._collateral (contracts/BatchedBancorMarketMaker.sol#801) is too similar to BatchedBancorMarketMaker.collaterals (contracts/BatchedBancorMarketMaker.sol#94)
Variable BatchedBancorMarketMaker._userIsSeller(uint256,address,address)._collateral (contracts/BatchedBancorMarketMaker.sol#474) is too similar to BatchedBancorMarketMaker.collaterals (contracts/BatchedBancorMarketMaker.sol#94)
Variable BatchedBancorMarketMaker.updateCollateralToken(address,uint256,uint256,uint32,uint256)._collateral (contracts/BatchedBancorMarketMaker.sol#256) is too similar to BatchedBancorMarketMaker.collaterals (contracts/BatchedBancorMarketMaker.sol#94)
Variable BatchedBancorMarketMaker._batchIsCancelled(uint256,address)._collateral (contracts/BatchedBancorMarketMaker.sol#465) is too similar to BatchedBancorMarketMaker.collaterals (contracts/BatchedBancorMarketMaker.sol#94)
Variable BatchedBancorMarketMaker.withdrawCollateral(address,uint256)._collateral (contracts/BatchedBancorMarketMaker.sol#397) is too similar to BatchedBancorMarketMaker.collaterals (contracts/BatchedBancorMarketMaker.sol#94)
Variable BatchedBancorMarketMaker.claimBuyOrder(address,uint256,address)._collateral (contracts/BatchedBancorMarketMaker.sol#305) is too similar to BatchedBancorMarketMaker.collaterals (contracts/BatchedBancorMarketMaker.sol#94)
Variable BatchedBancorMarketMaker._currentBatch(address)._collateral (contracts/BatchedBancorMarketMaker.sol#555) is too similar to BatchedBancorMarketMaker.collaterals (contracts/BatchedBancorMarketMaker.sol#94)
Variable BatchedBancorMarketMaker._claimSellOrder(address,uint256,address)._collateral (contracts/BatchedBancorMarketMaker.sol#781) is too similar to BatchedBancorMarketMaker.collaterals (contracts/BatchedBancorMarketMaker.sol#94)
Variable BatchedBancorMarketMaker._collateralIsWhitelisted(address)._collateral (contracts/BatchedBancorMarketMaker.sol#457) is too similar to BatchedBancorMarketMaker.collaterals (contracts/BatchedBancorMarketMaker.sol#94)
Variable BatchedBancorMarketMaker._openSellOrder(address,address,uint256)._collateral (contracts/BatchedBancorMarketMaker.sol#737) is too similar to BatchedBancorMarketMaker.collaterals (contracts/BatchedBancorMarketMaker.sol#94)
Variable BatchedBancorMarketMaker.openBuyOrder(address,address,uint256)._collateral (contracts/BatchedBancorMarketMaker.sol#274) is too similar to BatchedBancorMarketMaker.collaterals (contracts/BatchedBancorMarketMaker.sol#94)
Variable BatchedBancorMarketMaker._updatePricing(BatchedBancorMarketMaker.Batch,uint256,address)._collateral (contracts/BatchedBancorMarketMaker.sol#831) is too similar to BatchedBancorMarketMaker.collaterals (contracts/BatchedBancorMarketMaker.sol#94)
Variable BatchedBancorMarketMaker.removeCollateralToken(address)._collateral (contracts/BatchedBancorMarketMaker.sol#242) is too similar to BatchedBancorMarketMaker.collaterals (contracts/BatchedBancorMarketMaker.sol#94)
Variable BatchedBancorMarketMaker._updateCollateralToken(address,uint256,uint256,uint32,uint256)._collateral (contracts/BatchedBancorMarketMaker.sol#687) is too similar to BatchedBancorMarketMaker.collaterals (contracts/BatchedBancorMarketMaker.sol#94)
Variable BatchedBancorMarketMaker._claimCancelledSellOrder(address,uint256,address)._collateral (contracts/BatchedBancorMarketMaker.sol#816) is too similar to BatchedBancorMarketMaker.collaterals (contracts/BatchedBancorMarketMaker.sol#94)
Variable BatchedBancorMarketMaker._claimBuyOrder(address,uint256,address)._collateral (contracts/BatchedBancorMarketMaker.sol#766) is too similar to BatchedBancorMarketMaker.collaterals (contracts/BatchedBancorMarketMaker.sol#94)
Variable BatchedBancorMarketMaker._addCollateralToken(address,uint256,uint256,uint32,uint256)._collateral (contracts/BatchedBancorMarketMaker.sol#661) is too similar to BatchedBancorMarketMaker.collaterals (contracts/BatchedBancorMarketMaker.sol#94)
Variable BatchedBancorMarketMaker._cancelCurrentBatch(address)._collateral (contracts/BatchedBancorMarketMaker.sol#647) is too similar to BatchedBancorMarketMaker.collaterals (contracts/BatchedBancorMarketMaker.sol#94)
Variable BatchedBancorMarketMaker.claimSellOrder(address,uint256,address)._collateral (contracts/BatchedBancorMarketMaker.sol#320) is too similar to BatchedBancorMarketMaker.collaterals (contracts/BatchedBancorMarketMaker.sol#94)
Variable BatchedBancorMarketMaker.claimCancelledBuyOrder(address,uint256,address)._collateral (contracts/BatchedBancorMarketMaker.sol#335) is too similar to BatchedBancorMarketMaker.collaterals (contracts/BatchedBancorMarketMaker.sol#94)
Variable BatchedBancorMarketMaker._collateralValueIsValid(address,address,uint256)._collateral (contracts/BatchedBancorMarketMaker.sol#442) is too similar to BatchedBancorMarketMaker.collaterals (contracts/BatchedBancorMarketMaker.sol#94)
Variable BatchedBancorMarketMaker.claimCancelledSellOrder(address,uint256,address)._collateral (contracts/BatchedBancorMarketMaker.sol#348) is too similar to BatchedBancorMarketMaker.collaterals (contracts/BatchedBancorMarketMaker.sol#94)
Variable BatchedBancorMarketMaker.getCollateralToken(address)._collateral (contracts/BatchedBancorMarketMaker.sol#361) is too similar to BatchedBancorMarketMaker.collaterals (contracts/BatchedBancorMarketMaker.sol#94)
Reference: https://github.com/crytic/slither/wiki/Detector-Documentation#variable-names-are-too-similar

BatchedBancorMarketMaker.slitherConstructorConstantVariables() (contracts/BatchedBancorMarketMaker.sol#14-901) uses literals with too many digits:
        - PPM = 1000000 (contracts/BatchedBancorMarketMaker.sol#26)
BancorFormula.generalExp(uint256,uint8) (contracts/bancor-formula/BancorFormula.sol#405-443) uses literals with too many digits:
        - res += xi * 0x3442c4e6074a82f1797f72ac0000000 (contracts/bancor-formula/BancorFormula.sol#409)
BancorFormula.generalExp(uint256,uint8) (contracts/bancor-formula/BancorFormula.sol#405-443) uses literals with too many digits:
        - res += xi * 0x116b96f757c380fb287fd0e40000000 (contracts/bancor-formula/BancorFormula.sol#410)
BancorFormula.generalExp(uint256,uint8) (contracts/bancor-formula/BancorFormula.sol#405-443) uses literals with too many digits:
        - res += xi * 0x045ae5bdd5f0e03eca1ff4390000000 (contracts/bancor-formula/BancorFormula.sol#411)
BancorFormula.generalExp(uint256,uint8) (contracts/bancor-formula/BancorFormula.sol#405-443) uses literals with too many digits:
        - res += xi * 0x00defabf91302cd95b9ffda50000000 (contracts/bancor-formula/BancorFormula.sol#412)
BancorFormula.generalExp(uint256,uint8) (contracts/bancor-formula/BancorFormula.sol#405-443) uses literals with too many digits:
        - res += xi * 0x002529ca9832b22439efff9b8000000 (contracts/bancor-formula/BancorFormula.sol#413)
BancorFormula.generalExp(uint256,uint8) (contracts/bancor-formula/BancorFormula.sol#405-443) uses literals with too many digits:
        - res += xi * 0x00054f1cf12bd04e516b6da88000000 (contracts/bancor-formula/BancorFormula.sol#414)
BancorFormula.generalExp(uint256,uint8) (contracts/bancor-formula/BancorFormula.sol#405-443) uses literals with too many digits:
        - res += xi * 0x0000a9e39e257a09ca2d6db51000000 (contracts/bancor-formula/BancorFormula.sol#415)
BancorFormula.generalExp(uint256,uint8) (contracts/bancor-formula/BancorFormula.sol#405-443) uses literals with too many digits:
        - res += xi * 0x000012e066e7b839fa050c309000000 (contracts/bancor-formula/BancorFormula.sol#416)
BancorFormula.generalExp(uint256,uint8) (contracts/bancor-formula/BancorFormula.sol#405-443) uses literals with too many digits:
        - res += xi * 0x000001e33d7d926c329a1ad1a800000 (contracts/bancor-formula/BancorFormula.sol#417)
BancorFormula.generalExp(uint256,uint8) (contracts/bancor-formula/BancorFormula.sol#405-443) uses literals with too many digits:
        - res += xi * 0x0000002bee513bdb4a6b19b5f800000 (contracts/bancor-formula/BancorFormula.sol#418)
BancorFormula.generalExp(uint256,uint8) (contracts/bancor-formula/BancorFormula.sol#405-443) uses literals with too many digits:
        - res += xi * 0x00000003a9316fa79b88eccf2a00000 (contracts/bancor-formula/BancorFormula.sol#419)
BancorFormula.generalExp(uint256,uint8) (contracts/bancor-formula/BancorFormula.sol#405-443) uses literals with too many digits:
        - res += xi * 0x0000000048177ebe1fa812375200000 (contracts/bancor-formula/BancorFormula.sol#420)
BancorFormula.generalExp(uint256,uint8) (contracts/bancor-formula/BancorFormula.sol#405-443) uses literals with too many digits:
        - res += xi * 0x0000000005263fe90242dcbacf00000 (contracts/bancor-formula/BancorFormula.sol#421)
BancorFormula.generalExp(uint256,uint8) (contracts/bancor-formula/BancorFormula.sol#405-443) uses literals with too many digits:
        - res += xi * 0x000000000057e22099c030d94100000 (contracts/bancor-formula/BancorFormula.sol#422)
BancorFormula.generalExp(uint256,uint8) (contracts/bancor-formula/BancorFormula.sol#405-443) uses literals with too many digits:
        - res += xi * 0x0000000000057e22099c030d9410000 (contracts/bancor-formula/BancorFormula.sol#423)
BancorFormula.generalExp(uint256,uint8) (contracts/bancor-formula/BancorFormula.sol#405-443) uses literals with too many digits:
        - res += xi * 0x00000000000052b6b54569976310000 (contracts/bancor-formula/BancorFormula.sol#424)
BancorFormula.generalExp(uint256,uint8) (contracts/bancor-formula/BancorFormula.sol#405-443) uses literals with too many digits:
        - res += xi * 0x00000000000004985f67696bf748000 (contracts/bancor-formula/BancorFormula.sol#425)
BancorFormula.generalExp(uint256,uint8) (contracts/bancor-formula/BancorFormula.sol#405-443) uses literals with too many digits:
        - res += xi * 0x000000000000003dea12ea99e498000 (contracts/bancor-formula/BancorFormula.sol#426)
BancorFormula.generalExp(uint256,uint8) (contracts/bancor-formula/BancorFormula.sol#405-443) uses literals with too many digits:
        - res += xi * 0x00000000000000031880f2214b6e000 (contracts/bancor-formula/BancorFormula.sol#427)
BancorFormula.generalExp(uint256,uint8) (contracts/bancor-formula/BancorFormula.sol#405-443) uses literals with too many digits:
        - res += xi * 0x000000000000000025bcff56eb36000 (contracts/bancor-formula/BancorFormula.sol#428)
BancorFormula.generalExp(uint256,uint8) (contracts/bancor-formula/BancorFormula.sol#405-443) uses literals with too many digits:
        - res += xi * 0x000000000000000001b722e10ab1000 (contracts/bancor-formula/BancorFormula.sol#429)
BancorFormula.generalExp(uint256,uint8) (contracts/bancor-formula/BancorFormula.sol#405-443) uses literals with too many digits:
        - res += xi * 0x0000000000000000001317c70077000 (contracts/bancor-formula/BancorFormula.sol#430)
BancorFormula.generalExp(uint256,uint8) (contracts/bancor-formula/BancorFormula.sol#405-443) uses literals with too many digits:
        - res += xi * 0x00000000000000000000cba84aafa00 (contracts/bancor-formula/BancorFormula.sol#431)
BancorFormula.generalExp(uint256,uint8) (contracts/bancor-formula/BancorFormula.sol#405-443) uses literals with too many digits:
        - res += xi * 0x00000000000000000000082573a0a00 (contracts/bancor-formula/BancorFormula.sol#432)
BancorFormula.generalExp(uint256,uint8) (contracts/bancor-formula/BancorFormula.sol#405-443) uses literals with too many digits:
        - res += xi * 0x00000000000000000000005035ad900 (contracts/bancor-formula/BancorFormula.sol#433)
BancorFormula.generalExp(uint256,uint8) (contracts/bancor-formula/BancorFormula.sol#405-443) uses literals with too many digits:
        - res += xi * 0x000000000000000000000002f881b00 (contracts/bancor-formula/BancorFormula.sol#434)
BancorFormula.generalExp(uint256,uint8) (contracts/bancor-formula/BancorFormula.sol#405-443) uses literals with too many digits:
        - res += xi * 0x0000000000000000000000001b29340 (contracts/bancor-formula/BancorFormula.sol#435)
BancorFormula.generalExp(uint256,uint8) (contracts/bancor-formula/BancorFormula.sol#405-443) uses literals with too many digits:
        - res += xi * 0x00000000000000000000000000efc40 (contracts/bancor-formula/BancorFormula.sol#436)
BancorFormula.generalExp(uint256,uint8) (contracts/bancor-formula/BancorFormula.sol#405-443) uses literals with too many digits:
        - res += xi * 0x0000000000000000000000000007fe0 (contracts/bancor-formula/BancorFormula.sol#437)
BancorFormula.generalExp(uint256,uint8) (contracts/bancor-formula/BancorFormula.sol#405-443) uses literals with too many digits:
        - res += xi * 0x0000000000000000000000000000420 (contracts/bancor-formula/BancorFormula.sol#438)
BancorFormula.generalExp(uint256,uint8) (contracts/bancor-formula/BancorFormula.sol#405-443) uses literals with too many digits:
        - res += xi * 0x0000000000000000000000000000021 (contracts/bancor-formula/BancorFormula.sol#439)
BancorFormula.generalExp(uint256,uint8) (contracts/bancor-formula/BancorFormula.sol#405-443) uses literals with too many digits:
        - res += xi * 0x0000000000000000000000000000001 (contracts/bancor-formula/BancorFormula.sol#440)
BancorFormula.generalExp(uint256,uint8) (contracts/bancor-formula/BancorFormula.sol#405-443) uses literals with too many digits:
        - res / 0x688589cc0e9505e2f2fee5580000000 + _x + (ONE << _precision) (contracts/bancor-formula/BancorFormula.sol#442)
BancorFormula.optimalLog(uint256) (contracts/bancor-formula/BancorFormula.sol#456-484) uses literals with too many digits:
        - res += 0x40000000000000000000000000000000 (contracts/bancor-formula/BancorFormula.sol#463)
BancorFormula.optimalLog(uint256) (contracts/bancor-formula/BancorFormula.sol#456-484) uses literals with too many digits:
        - res += 0x20000000000000000000000000000000 (contracts/bancor-formula/BancorFormula.sol#464)
BancorFormula.optimalLog(uint256) (contracts/bancor-formula/BancorFormula.sol#456-484) uses literals with too many digits:
        - res += 0x10000000000000000000000000000000 (contracts/bancor-formula/BancorFormula.sol#465)
BancorFormula.optimalLog(uint256) (contracts/bancor-formula/BancorFormula.sol#456-484) uses literals with too many digits:
        - res += 0x08000000000000000000000000000000 (contracts/bancor-formula/BancorFormula.sol#466)
BancorFormula.optimalLog(uint256) (contracts/bancor-formula/BancorFormula.sol#456-484) uses literals with too many digits:
        - res += 0x04000000000000000000000000000000 (contracts/bancor-formula/BancorFormula.sol#467)
BancorFormula.optimalLog(uint256) (contracts/bancor-formula/BancorFormula.sol#456-484) uses literals with too many digits:
        - res += 0x02000000000000000000000000000000 (contracts/bancor-formula/BancorFormula.sol#468)
BancorFormula.optimalLog(uint256) (contracts/bancor-formula/BancorFormula.sol#456-484) uses literals with too many digits:
        - res += 0x01000000000000000000000000000000 (contracts/bancor-formula/BancorFormula.sol#469)
BancorFormula.optimalLog(uint256) (contracts/bancor-formula/BancorFormula.sol#456-484) uses literals with too many digits:
        - res += 0x00800000000000000000000000000000 (contracts/bancor-formula/BancorFormula.sol#470)
BancorFormula.optimalLog(uint256) (contracts/bancor-formula/BancorFormula.sol#456-484) uses literals with too many digits:
        - res += z * (0x100000000000000000000000000000000 - y) / 0x100000000000000000000000000000000 (contracts/bancor-formula/BancorFormula.sol#474)
BancorFormula.optimalLog(uint256) (contracts/bancor-formula/BancorFormula.sol#456-484) uses literals with too many digits:
        - res += z * (0x0aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa - y) / 0x200000000000000000000000000000000 (contracts/bancor-formula/BancorFormula.sol#475)
BancorFormula.optimalLog(uint256) (contracts/bancor-formula/BancorFormula.sol#456-484) uses literals with too many digits:
        - res += z * (0x099999999999999999999999999999999 - y) / 0x300000000000000000000000000000000 (contracts/bancor-formula/BancorFormula.sol#476)
BancorFormula.optimalLog(uint256) (contracts/bancor-formula/BancorFormula.sol#456-484) uses literals with too many digits:
        - res += z * (0x092492492492492492492492492492492 - y) / 0x400000000000000000000000000000000 (contracts/bancor-formula/BancorFormula.sol#477)
BancorFormula.optimalLog(uint256) (contracts/bancor-formula/BancorFormula.sol#456-484) uses literals with too many digits:
        - res += z * (0x08e38e38e38e38e38e38e38e38e38e38e - y) / 0x500000000000000000000000000000000 (contracts/bancor-formula/BancorFormula.sol#478)
BancorFormula.optimalLog(uint256) (contracts/bancor-formula/BancorFormula.sol#456-484) uses literals with too many digits:
        - res += z * (0x08ba2e8ba2e8ba2e8ba2e8ba2e8ba2e8b - y) / 0x600000000000000000000000000000000 (contracts/bancor-formula/BancorFormula.sol#479)
BancorFormula.optimalLog(uint256) (contracts/bancor-formula/BancorFormula.sol#456-484) uses literals with too many digits:
        - res += z * (0x089d89d89d89d89d89d89d89d89d89d89 - y) / 0x700000000000000000000000000000000 (contracts/bancor-formula/BancorFormula.sol#480)
BancorFormula.optimalLog(uint256) (contracts/bancor-formula/BancorFormula.sol#456-484) uses literals with too many digits:
        - res += z * (0x088888888888888888888888888888888 - y) / 0x800000000000000000000000000000000 (contracts/bancor-formula/BancorFormula.sol#481)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) uses literals with too many digits:
        - z = y = x % 0x10000000000000000000000000000000 (contracts/bancor-formula/BancorFormula.sol#503)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) uses literals with too many digits:
        - res += z * 0x00000618fee9f800 (contracts/bancor-formula/BancorFormula.sol#511)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) uses literals with too many digits:
        - res += z * 0x0000009c197dcc00 (contracts/bancor-formula/BancorFormula.sol#512)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) uses literals with too many digits:
        - res += z * 0x0000000e30dce400 (contracts/bancor-formula/BancorFormula.sol#513)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) uses literals with too many digits:
        - res += z * 0x000000012ebd1300 (contracts/bancor-formula/BancorFormula.sol#514)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) uses literals with too many digits:
        - res += z * 0x0000000017499f00 (contracts/bancor-formula/BancorFormula.sol#515)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) uses literals with too many digits:
        - res += z * 0x0000000001a9d480 (contracts/bancor-formula/BancorFormula.sol#516)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) uses literals with too many digits:
        - res += z * 0x00000000001c6380 (contracts/bancor-formula/BancorFormula.sol#517)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) uses literals with too many digits:
        - res += z * 0x000000000001c638 (contracts/bancor-formula/BancorFormula.sol#518)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) uses literals with too many digits:
        - res += z * 0x0000000000001ab8 (contracts/bancor-formula/BancorFormula.sol#519)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) uses literals with too many digits:
        - res += z * 0x000000000000017c (contracts/bancor-formula/BancorFormula.sol#520)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) uses literals with too many digits:
        - res += z * 0x0000000000000014 (contracts/bancor-formula/BancorFormula.sol#521)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) uses literals with too many digits:
        - res += z * 0x0000000000000001 (contracts/bancor-formula/BancorFormula.sol#522)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) uses literals with too many digits:
        - (x & 0x010000000000000000000000000000000) != 0 (contracts/bancor-formula/BancorFormula.sol#525)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) uses literals with too many digits:
        - (x & 0x020000000000000000000000000000000) != 0 (contracts/bancor-formula/BancorFormula.sol#526)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) uses literals with too many digits:
        - (x & 0x040000000000000000000000000000000) != 0 (contracts/bancor-formula/BancorFormula.sol#527)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) uses literals with too many digits:
        - (x & 0x080000000000000000000000000000000) != 0 (contracts/bancor-formula/BancorFormula.sol#528)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) uses literals with too many digits:
        - (x & 0x100000000000000000000000000000000) != 0 (contracts/bancor-formula/BancorFormula.sol#529)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) uses literals with too many digits:
        - (x & 0x200000000000000000000000000000000) != 0 (contracts/bancor-formula/BancorFormula.sol#530)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) uses literals with too many digits:
        - (x & 0x400000000000000000000000000000000) != 0 (contracts/bancor-formula/BancorFormula.sol#531)
BancorFormula.optimalExp(uint256) (contracts/bancor-formula/BancorFormula.sol#497-534) uses literals with too many digits:
        - res = res * 0x0002bf84208204f5977f9a8cf01fdc307 / 0x0000003c6ab775dd0b95b4cbee7e65d11 (contracts/bancor-formula/BancorFormula.sol#531)
BancorFormula.slitherConstructorConstantVariables() (contracts/bancor-formula/BancorFormula.sol#8-543) uses literals with too many digits:
        - MAX_RATIO = 1000000 (contracts/bancor-formula/BancorFormula.sol#15)
BancorFormula.slitherConstructorConstantVariables() (contracts/bancor-formula/BancorFormula.sol#8-543) uses literals with too many digits:
        - FIXED_1 = 0x080000000000000000000000000000000 (contracts/bancor-formula/BancorFormula.sol#22)
BancorFormula.slitherConstructorConstantVariables() (contracts/bancor-formula/BancorFormula.sol#8-543) uses literals with too many digits:
        - FIXED_2 = 0x100000000000000000000000000000000 (contracts/bancor-formula/BancorFormula.sol#23)
BancorFormula.slitherConstructorConstantVariables() (contracts/bancor-formula/BancorFormula.sol#8-543) uses literals with too many digits:
        - MAX_NUM = 0x200000000000000000000000000000000 (contracts/bancor-formula/BancorFormula.sol#24)
BancorFormula.slitherConstructorConstantVariables() (contracts/bancor-formula/BancorFormula.sol#8-543) uses literals with too many digits:
        - OPT_EXP_MAX_VAL = 0x800000000000000000000000000000000 (contracts/bancor-formula/BancorFormula.sol#36)
Reference: https://github.com/crytic/slither/wiki/Detector-Documentation#too-many-digits

BatchedBancorMarketMaker.ERROR_CONTRACT_IS_EOA (contracts/BatchedBancorMarketMaker.sol#28) is never used in BatchedBancorMarketMaker (contracts/BatchedBancorMarketMaker.sol#14-901)
BatchedBancorMarketMaker.ERROR_INVALID_TM_SETTING (contracts/BatchedBancorMarketMaker.sol#33) is never used in BatchedBancorMarketMaker (contracts/BatchedBancorMarketMaker.sol#14-901)
BatchedBancorMarketMaker.ERROR_TRANSFER_FROM_FAILED (contracts/BatchedBancorMarketMaker.sol#46) is never used in BatchedBancorMarketMaker (contracts/BatchedBancorMarketMaker.sol#14-901)
Reference: https://github.com/crytic/slither/wiki/Detector-Documentation#unused-state-variable

BancorFormula.version (contracts/bancor-formula/BancorFormula.sol#12) should be constant
Reference: https://github.com/crytic/slither/wiki/Detector-Documentation#state-variables-that-could-be-declared-constant

grantRole(bytes32,address) should be declared external:
        - AccessControl.grantRole(bytes32,address) (node_modules/@openzeppelin/contracts/access/AccessControl.sol#144-146)
revokeRole(bytes32,address) should be declared external:
        - AccessControl.revokeRole(bytes32,address) (node_modules/@openzeppelin/contracts/access/AccessControl.sol#159-161)
renounceRole(bytes32,address) should be declared external:
        - AccessControl.renounceRole(bytes32,address) (node_modules/@openzeppelin/contracts/access/AccessControl.sol#179-183)
getRoleMember(bytes32,uint256) should be declared external:
        - AccessControlEnumerable.getRoleMember(bytes32,uint256) (node_modules/@openzeppelin/contracts/access/AccessControlEnumerable.sol#37-39)
getRoleMemberCount(bytes32) should be declared external:
        - AccessControlEnumerable.getRoleMemberCount(bytes32) (node_modules/@openzeppelin/contracts/access/AccessControlEnumerable.sol#45-47)
name() should be declared external:
        - ERC20.name() (node_modules/@openzeppelin/contracts/token/ERC20/ERC20.sol#62-64)
symbol() should be declared external:
        - ERC20.symbol() (node_modules/@openzeppelin/contracts/token/ERC20/ERC20.sol#70-72)
decimals() should be declared external:
        - ERC20.decimals() (node_modules/@openzeppelin/contracts/token/ERC20/ERC20.sol#87-89)
totalSupply() should be declared external:
        - ERC20.totalSupply() (node_modules/@openzeppelin/contracts/token/ERC20/ERC20.sol#94-96)
balanceOf(address) should be declared external:
        - ERC20.balanceOf(address) (node_modules/@openzeppelin/contracts/token/ERC20/ERC20.sol#101-103)
transfer(address,uint256) should be declared external:
        - ERC20.transfer(address,uint256) (node_modules/@openzeppelin/contracts/token/ERC20/ERC20.sol#113-117)
approve(address,uint256) should be declared external:
        - ERC20.approve(address,uint256) (node_modules/@openzeppelin/contracts/token/ERC20/ERC20.sol#136-140)
transferFrom(address,address,uint256) should be declared external:
        - ERC20.transferFrom(address,address,uint256) (node_modules/@openzeppelin/contracts/token/ERC20/ERC20.sol#158-167)
increaseAllowance(address,uint256) should be declared external:
        - ERC20.increaseAllowance(address,uint256) (node_modules/@openzeppelin/contracts/token/ERC20/ERC20.sol#181-185)
decreaseAllowance(address,uint256) should be declared external:
        - ERC20.decreaseAllowance(address,uint256) (node_modules/@openzeppelin/contracts/token/ERC20/ERC20.sol#201-210)
burn(uint256) should be declared external:
        - ERC20Burnable.burn(uint256) (node_modules/@openzeppelin/contracts/token/ERC20/extensions/ERC20Burnable.sol#20-22)
burnFrom(address,uint256) should be declared external:
        - ERC20Burnable.burnFrom(address,uint256) (node_modules/@openzeppelin/contracts/token/ERC20/extensions/ERC20Burnable.sol#35-38)
balanceOf(address) should be declared external:
        - ERC721.balanceOf(address) (node_modules/@openzeppelin/contracts/token/ERC721/ERC721.sol#62-65)
name() should be declared external:
        - ERC721.name() (node_modules/@openzeppelin/contracts/token/ERC721/ERC721.sol#79-81)
symbol() should be declared external:
        - ERC721.symbol() (node_modules/@openzeppelin/contracts/token/ERC721/ERC721.sol#86-88)
tokenURI(uint256) should be declared external:
        - ERC721.tokenURI(uint256) (node_modules/@openzeppelin/contracts/token/ERC721/ERC721.sol#93-98)
approve(address,uint256) should be declared external:
        - ERC721.approve(address,uint256) (node_modules/@openzeppelin/contracts/token/ERC721/ERC721.sol#112-122)
setApprovalForAll(address,bool) should be declared external:
        - ERC721.setApprovalForAll(address,bool) (node_modules/@openzeppelin/contracts/token/ERC721/ERC721.sol#136-138)
transferFrom(address,address,uint256) should be declared external:
        - ERC721.transferFrom(address,address,uint256) (node_modules/@openzeppelin/contracts/token/ERC721/ERC721.sol#150-159)
safeTransferFrom(address,address,uint256) should be declared external:
        - ERC721.safeTransferFrom(address,address,uint256) (node_modules/@openzeppelin/contracts/token/ERC721/ERC721.sol#164-170)
mint(address,uint256) should be declared external:
        - ERC20Token.mint(address,uint256) (contracts/ERC20Token.sol#47-51)
pause() should be declared external:
        - ERC20Token.pause() (contracts/ERC20Token.sol#62-65)
unpause() should be declared external:
        - ERC20Token.unpause() (contracts/ERC20Token.sol#76-79)
mint(address,uint256) should be declared external:
        - TestDAI.mint(address,uint256) (contracts/TestDAI.sol#42-46)
calculatePurchaseReturn(uint256,uint256,uint32,uint256) should be declared external:
        - BancorFormula.calculatePurchaseReturn(uint256,uint256,uint32,uint256) (contracts/bancor-formula/BancorFormula.sol#187-205)
        - IBancorFormula.calculatePurchaseReturn(uint256,uint256,uint32,uint256) (contracts/bancor-formula/interfaces/IBancorFormula.sol#8)
calculateSaleReturn(uint256,uint256,uint32,uint256) should be declared external:
        - BancorFormula.calculateSaleReturn(uint256,uint256,uint32,uint256) (contracts/bancor-formula/BancorFormula.sol#221-244)
        - IBancorFormula.calculateSaleReturn(uint256,uint256,uint32,uint256) (contracts/bancor-formula/interfaces/IBancorFormula.sol#9)
calculateCrossConnectorReturn(uint256,uint32,uint256,uint32,uint256) should be declared external:
        - BancorFormula.calculateCrossConnectorReturn(uint256,uint32,uint256,uint32,uint256) (contracts/bancor-formula/BancorFormula.sol#539-541)
Reference: https://github.com/crytic/slither/wiki/Detector-Documentation#public-function-that-could-be-declared-external
. analyzed (30 contracts with 78 detectors), 344 result(s) found
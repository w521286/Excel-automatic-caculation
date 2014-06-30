Excel-automatic-caculation
==========================

Excel automatic caculation
1、FormulaEvaluator evaluator = cell.getSheet().getWorkbook().getCreationHelper().createFormulaEvaluator();
		evaluator.evaluateFormulaCell(cell);
2、不一定起作用
  cell.getSheet().setForceFormulaRecalculation(true);

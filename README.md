Excel-automatic-caculation
==========================

1、FormulaEvaluator evaluator = cell.getSheet().getWorkbook().getCreationHelper().createFormulaEvaluator();   <br>
      evaluator.evaluateFormulaCell(cell);   <br>
2、不一定起作用   <br>
  cell.getSheet().setForceFormulaRecalculation(true);    


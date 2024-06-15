

SRC_FILES:= \
	Source/Bimodal_Table.v \
	Source/BranchAddress.v \
	Source/Comparator.v \
	Source/Incrementer.v \
	Source/Index_Tag_Generator.v \
	Source/Statistics.v \
	Source/TAGE_Controller.v \
	Source/TAGE_Table.v \
	Source/TopLevel.v \
	Source/TopLevel_testbench.v \
	Source/prediction.v \
	Source/update_history.v \
	Source/update_predictor.v

build_tage2_tb: 
	iverilog -o out/tage2_tb.out $(SRC_FILES)

run_tage2_tb: build_aes1_tb
	./out/tage2_tb.out

clean:
	rm -rf out/*



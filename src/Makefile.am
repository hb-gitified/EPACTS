## Additional flags to pass to aclocal when it is invoked automatically at
## make time. The ${ACLOCAL_FLAGS} variable is picked up from the environment
## to provide a way for the user to supply additional arguments.
ACLOCAL_AMFLAGS = -I m4 ${ACLOCAL_FLAGS}

## Paths to include
TABIX_VER = 0.2.5
TABIX = tabix-$(TABIX_VER)
AM_CPPFLAGS = -Wall -fpic -O2 #-I../include/ #-I$(TABIX)/

EIGEN_HEADER_FILES = Eigen/src/Cholesky Eigen/src/Cholesky/LDLT.h Eigen/src/Cholesky/LLT.h Eigen/src/Core Eigen/src/Core/arch Eigen/src/Core/arch/AltiVec Eigen/src/Core/arch/AltiVec/Complex.h Eigen/src/Core/arch/AltiVec/PacketMath.h Eigen/src/Core/arch/Default Eigen/src/Core/arch/Default/Settings.h Eigen/src/Core/arch/NEON Eigen/src/Core/arch/NEON/Complex.h Eigen/src/Core/arch/NEON/PacketMath.h Eigen/src/Core/arch/SSE Eigen/src/Core/arch/SSE/Complex.h Eigen/src/Core/arch/SSE/MathFunctions.h Eigen/src/Core/arch/SSE/PacketMath.h Eigen/src/Core/products Eigen/src/Core/products/CoeffBasedProduct.h Eigen/src/Core/products/GeneralBlockPanelKernel.h Eigen/src/Core/products/GeneralMatrixMatrix.h Eigen/src/Core/products/GeneralMatrixMatrixTriangular.h Eigen/src/Core/products/GeneralMatrixVector.h Eigen/src/Core/products/Parallelizer.h Eigen/src/Core/products/SelfadjointMatrixMatrix.h Eigen/src/Core/products/SelfadjointMatrixVector.h Eigen/src/Core/products/SelfadjointProduct.h Eigen/src/Core/products/SelfadjointRank2Update.h Eigen/src/Core/products/TriangularMatrixMatrix.h Eigen/src/Core/products/TriangularMatrixVector.h Eigen/src/Core/products/TriangularSolverMatrix.h Eigen/src/Core/products/TriangularSolverVector.h Eigen/src/Core/util Eigen/src/Core/util/BlasUtil.h Eigen/src/Core/util/Constants.h Eigen/src/Core/util/DisableStupidWarnings.h Eigen/src/Core/util/ForwardDeclarations.h Eigen/src/Core/util/Macros.h Eigen/src/Core/util/Memory.h Eigen/src/Core/util/Meta.h Eigen/src/Core/util/ReenableStupidWarnings.h Eigen/src/Core/util/StaticAssert.h Eigen/src/Core/util/XprHelper.h Eigen/src/Core/Array.h Eigen/src/Core/ArrayBase.h Eigen/src/Core/Visitor.h Eigen/src/Core/ArrayWrapper.h Eigen/src/Core/Assign.h Eigen/src/Core/BandMatrix.h Eigen/src/Core/Block.h Eigen/src/Core/VectorwiseOp.h Eigen/src/Core/BooleanRedux.h Eigen/src/Core/CommaInitializer.h Eigen/src/Core/CwiseBinaryOp.h Eigen/src/Core/CwiseNullaryOp.h Eigen/src/Core/CwiseUnaryOp.h Eigen/src/Core/CwiseUnaryView.h Eigen/src/Core/DenseBase.h Eigen/src/Core/DenseCoeffsBase.h Eigen/src/Core/DenseStorage.h Eigen/src/Core/Diagonal.h Eigen/src/Core/DiagonalMatrix.h Eigen/src/Core/DiagonalProduct.h Eigen/src/Core/Dot.h Eigen/src/Core/EigenBase.h Eigen/src/Core/Flagged.h Eigen/src/Core/ForceAlignedAccess.h Eigen/src/Core/Functors.h Eigen/src/Core/Fuzzy.h Eigen/src/Core/GenericPacketMath.h Eigen/src/Core/GlobalFunctions.h Eigen/src/Core/IO.h Eigen/src/Core/Map.h Eigen/src/Core/MapBase.h Eigen/src/Core/MathFunctions.h Eigen/src/Core/Matrix.h Eigen/src/Core/MatrixBase.h Eigen/src/Core/NestByValue.h Eigen/src/Core/NoAlias.h Eigen/src/Core/NumTraits.h Eigen/src/Core/PermutationMatrix.h Eigen/src/Core/PlainObjectBase.h Eigen/src/Core/Product.h Eigen/src/Core/ProductBase.h Eigen/src/Core/Random.h Eigen/src/Core/Redux.h Eigen/src/Core/Replicate.h Eigen/src/Core/ReturnByValue.h Eigen/src/Core/Reverse.h Eigen/src/Core/Select.h Eigen/src/Core/SelfAdjointView.h Eigen/src/Core/SelfCwiseBinaryOp.h Eigen/src/Core/SolveTriangular.h Eigen/src/Core/StableNorm.h Eigen/src/Core/Stride.h Eigen/src/Core/Swap.h Eigen/src/Core/Transpose.h Eigen/src/Core/Transpositions.h Eigen/src/Core/TriangularMatrix.h Eigen/src/Core/VectorBlock.h Eigen/src/Eigen2Support Eigen/src/Eigen2Support/Geometry Eigen/src/Eigen2Support/Geometry/AlignedBox.h Eigen/src/Eigen2Support/Geometry/All.h Eigen/src/Eigen2Support/Geometry/AngleAxis.h Eigen/src/Eigen2Support/Geometry/Hyperplane.h Eigen/src/Eigen2Support/Geometry/ParametrizedLine.h Eigen/src/Eigen2Support/Geometry/Quaternion.h Eigen/src/Eigen2Support/Geometry/Rotation2D.h Eigen/src/Eigen2Support/Geometry/RotationBase.h Eigen/src/Eigen2Support/Geometry/Scaling.h Eigen/src/Eigen2Support/Geometry/Transform.h Eigen/src/Eigen2Support/Geometry/Translation.h Eigen/src/Eigen2Support/Block.h Eigen/src/Eigen2Support/Cwise.h Eigen/src/Eigen2Support/CwiseOperators.h Eigen/src/Eigen2Support/LU.h Eigen/src/Eigen2Support/Lazy.h Eigen/src/Eigen2Support/LeastSquares.h Eigen/src/Eigen2Support/Macros.h Eigen/src/Eigen2Support/MathFunctions.h Eigen/src/Eigen2Support/Memory.h Eigen/src/Eigen2Support/Meta.h Eigen/src/Eigen2Support/Minor.h Eigen/src/Eigen2Support/QR.h Eigen/src/Eigen2Support/SVD.h Eigen/src/Eigen2Support/TriangularSolver.h Eigen/src/Eigen2Support/VectorBlock.h Eigen/src/Eigenvalues Eigen/src/Eigenvalues/ComplexEigenSolver.h Eigen/src/Eigenvalues/ComplexSchur.h Eigen/src/Eigenvalues/EigenSolver.h Eigen/src/Eigenvalues/EigenvaluesCommon.h Eigen/src/Eigenvalues/GeneralizedSelfAdjointEigenSolver.h Eigen/src/Eigenvalues/HessenbergDecomposition.h Eigen/src/Eigenvalues/MatrixBaseEigenvalues.h Eigen/src/Eigenvalues/RealSchur.h Eigen/src/Eigenvalues/SelfAdjointEigenSolver.h Eigen/src/Eigenvalues/Tridiagonalization.h Eigen/src/Geometry Eigen/src/Geometry/arch Eigen/src/Geometry/arch/Geometry_SSE.h Eigen/src/Geometry/AlignedBox.h Eigen/src/Geometry/AngleAxis.h Eigen/src/Geometry/EulerAngles.h Eigen/src/Geometry/Homogeneous.h Eigen/src/Geometry/Hyperplane.h Eigen/src/Geometry/OrthoMethods.h Eigen/src/Geometry/ParametrizedLine.h Eigen/src/Geometry/Quaternion.h Eigen/src/Geometry/Rotation2D.h Eigen/src/Geometry/RotationBase.h Eigen/src/Geometry/Scaling.h Eigen/src/Geometry/Transform.h Eigen/src/Geometry/Translation.h Eigen/src/Geometry/Umeyama.h Eigen/src/Householder Eigen/src/Householder/BlockHouseholder.h Eigen/src/Householder/Householder.h Eigen/src/Householder/HouseholderSequence.h Eigen/src/Jacobi Eigen/src/Jacobi/Jacobi.h Eigen/src/LU Eigen/src/LU/arch Eigen/src/LU/arch/Inverse_SSE.h Eigen/src/LU/Determinant.h Eigen/src/LU/FullPivLU.h Eigen/src/LU/Inverse.h Eigen/src/LU/PartialPivLU.h Eigen/src/QR Eigen/src/QR/ColPivHouseholderQR.h Eigen/src/QR/FullPivHouseholderQR.h Eigen/src/QR/HouseholderQR.h Eigen/src/SVD Eigen/src/SVD/JacobiSVD.h Eigen/src/SVD/UpperBidiagonalization.h Eigen/src/Sparse Eigen/src/Sparse/AmbiVector.h Eigen/src/Sparse/CompressedStorage.h Eigen/src/Sparse/CoreIterators.h Eigen/src/Sparse/DynamicSparseMatrix.h Eigen/src/Sparse/MappedSparseMatrix.h Eigen/src/Sparse/SparseAssign.h Eigen/src/Sparse/SparseBlock.h Eigen/src/Sparse/SparseCwiseBinaryOp.h Eigen/src/Sparse/SparseCwiseUnaryOp.h Eigen/src/Sparse/SparseDenseProduct.h Eigen/src/Sparse/SparseDiagonalProduct.h Eigen/src/Sparse/SparseDot.h Eigen/src/Sparse/SparseFuzzy.h Eigen/src/Sparse/SparseMatrix.h Eigen/src/Sparse/SparseMatrixBase.h Eigen/src/Sparse/SparseProduct.h Eigen/src/Sparse/SparseRedux.h Eigen/src/Sparse/SparseSelfAdjointView.h Eigen/src/Sparse/SparseSparseProduct.h Eigen/src/Sparse/SparseTranspose.h Eigen/src/Sparse/SparseTriangularView.h Eigen/src/Sparse/SparseUtil.h Eigen/src/Sparse/SparseVector.h Eigen/src/Sparse/SparseView.h Eigen/src/Sparse/TriangularSolver.h Eigen/src/StlSupport Eigen/src/StlSupport/StdDeque.h Eigen/src/StlSupport/StdList.h Eigen/src/StlSupport/StdVector.h Eigen/src/StlSupport/details.h Eigen/src/misc Eigen/src/misc/Image.h Eigen/src/misc/Kernel.h Eigen/src/misc/Solve.h Eigen/src/plugins Eigen/src/plugins/ArrayCwiseBinaryOps.h Eigen/src/plugins/ArrayCwiseUnaryOps.h Eigen/src/plugins/BlockMethods.h Eigen/src/plugins/CommonCwiseBinaryOps.h Eigen/src/plugins/CommonCwiseUnaryOps.h Eigen/src/plugins/MatrixCwiseBinaryOps.h Eigen/src/plugins/MatrixCwiseUnaryOps.h Eigen/Array Eigen/Cholesky Eigen/Core Eigen/Dense Eigen/Eigen Eigen/Eigen2Support Eigen/Eigenvalues Eigen/Geometry Eigen/Householder Eigen/Jacobi Eigen/LU Eigen/LeastSquares Eigen/QR Eigen/QtAlignedMalloc Eigen/SVD Eigen/Sparse Eigen/StdDeque Eigen/StdList Eigen/StdVector

noinst_HEADERS = hDist.h \
	sparseHMM.h icGraph.h pcHMM.h \
	AnnotationOutput.h \
	bam_endian.h boolParser.h Constant.h GeneFormat.h GenomeSequence.h \
	kseq.h ModelParser.h pException.h Range.h tabix.h \
	AnnotationResultCollection.h BedReader.h cdsStat.h Error.h Gene.h \
	GitVersion.h ksort.h ncStat.h pFile.h TabixReader.h AnnotationResult.h \
	bgix.h Codon.h FreqTable.h genomeLoci.h genomePosition.h IO.h kstring.h OrderedMap.h \
	PhredHelper.h SequenceUtil.h TypeConversion.h AnnotationString.h bgzf.h \
	codonHelper.h fVcf.h genomeScore.h khash.h locusStat.h Parameters.h Priority.h \
	StringTemplate.h Type.h Argument.h boolExprParser.h Common.h GeneAnnotation.h \
	GenomeScore.h LineBreaker.h knetfile.h LogFile.h pEmmax.h pVcf.h StringUtil.h \
	wFile.h \
	$(EIGEN_HEADER_FILES)

bin_PROGRAMS = pEmmax vcfast chaps anno bgzip tabix #$(TABIX)/bgzip $(TABIX)/tabix

noinst_LIBRARIES = libtabix.a

## pEmmax files
pEmmax_SOURCES = pEmmax.cpp Parameters.cpp Error.cpp PhredHelper.cpp codonHelper.cpp 
pEmmax_LDADD = libtabix.a

## vcfast files
vcfast_SOURCES = vcfast.cpp Error.cpp PhredHelper.cpp Parameters.cpp codonHelper.cpp genomePosition.cpp
vcfast_LDADD = libtabix.a

## chaps files
chaps_SOURCES = chaps.cpp Error.cpp PhredHelper.cpp Parameters.cpp
chaps_LDADD = libtabix.a

## anno files
anno_SOURCES = Anno.cpp IO.cpp
anno_LDADD = libtabix.a

bgzip_SOURCES = bgzip.c bedidx.c bgzf.c knetfile.c kstring.c

tabix_SOURCES = tabix.c bedidx.c bgzf.c knetfile.c kstring.c index.c

libtabix_a_SOURCES = bedidx.c bgzf.c knetfile.c kstring.c index.c

## building libtabix.a
#$(TABIX)/libtabix.a: ../data/$(TABIX).tar.bz2
#	tar xvjf ../data/$(TABIX).tar.bz2
#	cd $(TABIX)/; make; cd ..
#
#$(TABIX)/bgzip: $(TABIX)/libtabix.a
#
#$(TABIX)/tabix: $(TABIX)/libtabix.a

#clean-local:
#	rm -rf $(TABIX)

## Define an independent executable script for inclusion in the distribution
## archive. It will not be installed on an end user's system, however.
#dist_noinst_SCRIPTS = autogen.sh
